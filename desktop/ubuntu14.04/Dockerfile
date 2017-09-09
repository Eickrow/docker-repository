FROM ubuntu:14.04
RUN apt-get update  -y
RUN apt-get upgrade -y
RUN apt-get install -y build-essential
RUN apt-get install -y software-properties-common
RUN apt-get install -y byobu curl git htop man unzip vim wget
WORKDIR /root
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y lxde-core lxterminal tightvncserver
CMD ["bash"]
EXPOSE 5901