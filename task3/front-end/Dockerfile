FROM nginx:latest

# copie le dir du front à l'adresse indiqué dans docker
COPY ./softy-pinko-front-end/ /var/www/html/softy-pinko-front-end/
# copie le fichier de conf à l'emplacement indiqué
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
