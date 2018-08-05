FROM ubuntu
WORKDIR /app
COPY . .
RUN apt-get update && apt-get install -y nodejs && apt-get install -y npm
EXPOSE 4200

RUN npm install
CMD npm start