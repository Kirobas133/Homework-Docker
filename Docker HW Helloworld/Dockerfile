FROM ubuntu:latest
	LABEL mantainer="kirsos342@gmail.com"
	RUN apt-get update && apt-get install -y g++ nano net-tools
	WORKDIR /root/homework/
	COPY hellodockerworld.cpp .
	RUN g++ hellodockerworld.cpp -o hellodockerworld
	CMD ["./hellodockerworld"]