FROM souravkl11/raganork:test

RUN git clone https://github.com/abhi-ak77/KengBotz/ /skl/raganork
WORKDIR /skl/raganork 
ENV TZ = Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "raganork.js"]
