FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/Itxxwasi/wasiimd /root/wasiimd
WORKDIR /root/wasiimd/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]


 
