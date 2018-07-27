FROM ubuntu

RUN apt-get update && apt-get install -y nodejs && apt-get install -y npm
EXPOSE 3000
COPY /home/wesley/Documents/Express/MicroServiceTest/microservice/ /appServer
RUN cd appServer && npm install & npm start
CMD /bin/bash