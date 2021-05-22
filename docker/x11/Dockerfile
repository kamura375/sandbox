From ubuntu
RUN apt-get update
RUN apt-get install -y x11-apps
#VOLUME ~/.Xauthority:/root/.Xauthority
ENV DISPLAY "192.168.0.20:0"
CMD ["xeyes"]
