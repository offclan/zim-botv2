# We are just using WhatsAsena's Dockerfile
# Also the Base
# But We are not depending Asena for All
# Therefore WhatsAlexa is not a Fake bot of WhatsAsena
# © zim-botv2 made by team-zimbots

FROM fusuf/whatsasena:latest

RUN git clone https://github.com/zim-botv2 /root/WhatsAlexa
WORKDIR /root/WhatsAlexa/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
