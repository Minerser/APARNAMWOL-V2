FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Minerser/APARNAMWOL-V2/tree/master/APARNAMWOL /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
