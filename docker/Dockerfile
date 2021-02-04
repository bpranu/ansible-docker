FROM ubuntu:latest
RUN apt update && apt install inotify-tools gzip && apt install ssmtp -y
RUN mkdir incoming processed
ADD test.sh /
