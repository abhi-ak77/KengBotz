FROM fusuf/whatsasena:latest

RUN git clone https://github.com/abhi-ak77/KengBotz /skl/Raganork
WORKDIR /skl/KengBotz
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN npm install
CMD ["node", "index.js"]
