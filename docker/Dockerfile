FROM texlive/texlive:latest

RUN mkdir /code
WORKDIR /code

RUN apt-get update -y && apt-get upgrade -y
RUN apt-get install -y texlive-lang-japanese
RUN apt-get install -y fonts-noto-cjk fonts-noto-cjk-extra
RUN apt-get install -y fonts-ipaexfont-gothic fonts-ipaexfont-mincho
