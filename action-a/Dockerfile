From ubuntu/nginx

RUN apt-get update -y && apt-get dist-upgrade -y && apt-get upgrade -y
RUN apt-get remove -y wget gnupg
RUN apt-get autoremove -y
RUN rm -rf /var/lib/apt/lists/*

CMD ["bash"]
