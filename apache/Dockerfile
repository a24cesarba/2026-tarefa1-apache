FROM debian:12

RUN apt update && apt install -y apache2 && apt clean && rm -rf /var/lib/apt/lists/*

EXPOSE 80

CMD ["apache2ctl", "-D", "FOREGROUND"]

