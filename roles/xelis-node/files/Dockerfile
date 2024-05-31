FROM arm32v7/alpine

RUN	mkdir -p /opt/miners/xelis-node
WORKDIR /opt/miners/xelis-node

RUN	apk update
RUN apk add git
RUN apk add bash
RUN apk add curl

RUN git clone https://github.com/xelis-project/xelis-blockchain.git
#RUN curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y || true

#RUN cd xelis-blockchain && ./build_all.sh

RUN curl -L -o ./xelis-blockchain.tar.gz https://github.com/xelis-project/xelis-blockchain/releases/download/v1.9.5/armv7-unknown-linux-gnueabihf.tar.gz
RUN tar -xvzf ./xelis-blockchain.tar.gz

CMD tail -f /dev/null
