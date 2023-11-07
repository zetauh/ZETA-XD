FROM quay.io/maherzubair/sigma-md:beta
RUN git clone https://github.com/zetauh/ZETA-XD /root/zetauh/ZETA-XD
WORKDIR /root/zetauh/ZETA-XD/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
 
 
