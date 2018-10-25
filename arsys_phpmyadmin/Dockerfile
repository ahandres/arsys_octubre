FROM phpmyadmin/phpmyadmin:4.7.7-1

MAINTAINER ahandres

ARG filename
LABEL build_time_2="26/10/2918"
#Set TimeZone Madrid
ENV TZ=Europe/Madrid
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN touch ${filename}