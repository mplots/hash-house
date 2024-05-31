FROM ubuntu:latest

RUN apt-get update
RUN apt-get install git automake autotools-dev build-essential make libcurl4-openssl-dev libgmp3-dev zlib1g-dev -y
RUN git clone https://github.com/f1exlabs/cpuminer.git 
RUN cd cpuminer && ./build-armv8.sh