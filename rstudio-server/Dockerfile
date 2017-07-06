FROM rocker/tidyverse:3.4.1
MAINTAINER Daniel Herman <daniel.herman2@uphs.upenn.edu>

# RUN echo 'hermanda:tmppwd' | chpasswd
#RUN useradd --create-home --shell /bin/bash hermanda

RUN install2.r --error \
	--deps FALSE \
	logging \
	cowplot
