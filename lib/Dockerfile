# using suhail's docker coz mine have issues

FROM quay.io/suhailtechinfo/suhail-v2
RUN git clone https://github.com/ahmadtech12/AHMAD_MD_BOT/root/ahmadtech12/AHMAD_MD_BOT
WORKDIR /root/ahmadtech12/AHMAD_MD_BOT
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
