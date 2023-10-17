FROM ubuntu:latest
	LABEL mantainer="kirsos342@gmail.com"
	RUN apt-get update && apt-get install -y g++ clang nano net-tools
	WORKDIR /root/homework/
	COPY Homework9.1.cpp .
	RUN clang Homework9.1.cpp -o homework91clang -lstdc++
	CMD ["./homework91clang"]