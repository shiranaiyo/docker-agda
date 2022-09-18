FROM fpco/stack-build:lts-19.23

RUN stack --resolver=lts-19.23 install Agda-2.6.2.2
RUN sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys A4B469963BF863CC
RUN sudo add-apt-repository ppa:git-core/ppa
RUN sudo apt update
RUN sudo apt -y install git
