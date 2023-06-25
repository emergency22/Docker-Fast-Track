#FROM ubuntu:16.04
#RUN apt-get update
#RUN apt install curl -y
#RUN apt install ruby -y
#RUN apt install python -y
#RUN apt install build-essential -y
#RUN apt install apache2 -y

#Every single run instruction creates a new layer... We can instead put all the install statements on a single line with " && \ ", which will help save space

#FROM ubuntu:16.04
#RUN apt-get update && \
#apt install curl -y && \
#apt install ruby -y && \
#apt install python -y && \
#apt install build-essential -y && \
#apt install apache2 -y

#Additional image size saving... Changing OS (alpine) and changing syntax (apk vs apt-get) & (apk-add vs apt install)

FROM alpine
RUN apk update && \
apk add curl && \
apk add ruby && \
apk add python && \
apk add build-base && \
apk add apache2

#couldn't get this to work, but I get the concepts.