FROM ubuntu:latest

LABEL manteiner="Gabriele Martini <emaillllll@gmail.com> " \
	version="1.0.0" \
	license="GPLv2"

RUN apt update \ 
	&& whoami
RUN pwd

WORKDIR /var/www/html

COPY . .

USER www-data

ENTRYPOINT ["ls", "/etc/"]

CMD echo "Ciaone :-)"
