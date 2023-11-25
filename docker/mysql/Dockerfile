FROM --platform=linux/amd64 mysql:5.7

ENV DEBIAN_FRONTEND noninteractive
ENV TZ=Africa/Tunisia
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

EXPOSE 3306