FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Kalippan-minnu/saniyamol /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Kalippan-minnu/kalippanser

CMD ["node", "bot.js"]
