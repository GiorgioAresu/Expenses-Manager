FROM ubuntu:14.04

# Install Node.js
RUN apt-get -y update
RUN apt-get install -y nodejs npm

ADD . /src

RUN cd /src; npm install

ENV PORT 3001
ENV NODE_ENV development

EXPOSE 3001

#CMD ["node", "/src/server.js"]
