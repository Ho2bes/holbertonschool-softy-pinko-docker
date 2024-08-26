# Utiliser l'image Nginx
FROM nginx:latest

# Copier les fichiers du front-end dans le répertoire de Nginx
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copier le fichier de configuration Nginx
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
