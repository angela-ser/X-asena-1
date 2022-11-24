FROM quay.io/xelectra/xasena:latest
RUN git clone https://github.com/angela-ser/X-Asena-1 /root/HyNO
WORKDIR /root/HyNO/
RUN yarn install --network-concurrency 1

CMD ["node", "bot.js"] 
