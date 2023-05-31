FROM debian:latest

RUN	apt-get update
RUN	apt-get install build-essential -y
RUN	apt-get install hydra -y

RUN wget https://github.com/danielmiessler/SecLists/raw/master/Passwords/Leaked-Databases/rockyou.txt.tar.gz && \
	tar xf rockyou.txt.tar.gz
