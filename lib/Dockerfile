FROM quay.io/afx-abu/abu-md
RUN git clone https://github.com/Munaxxx/Abu-MD /root/Munaxxx/
WORKDIR /root/Munaxxx/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js"]
