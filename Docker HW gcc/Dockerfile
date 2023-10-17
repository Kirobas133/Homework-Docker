FROM gcc:latest
	LABEL mantainer="kirsos342@gmail.com"
	RUN apt-get update && apt-get install -y  nano net-tools
	WORKDIR /root/homework/
	COPY Homework9.1.cpp .
	RUN gcc -o Homework9.1 Homework9.1.cpp -lstdc++
	CMD ["./Homework9.1"]