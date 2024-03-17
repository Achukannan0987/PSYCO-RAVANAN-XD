FROM quay.io/loki-xer/jarvis-md:latest
RUN git clone https://github.com/Achukannan0986/PSYCO-RAVANAN-XD /root/psyco/
WORKDIR /root/psyco/
RUN yarn install --network-concurrency 1
CMD ["npm", "start"]
