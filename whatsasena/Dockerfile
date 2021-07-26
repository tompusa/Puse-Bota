FROM fusuf/whatsasena:latest

RUN git clone https://github.com/tompusa/Puse-Bota /root/Puse-Bota
WORKDIR /root/Puse-Bota/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
