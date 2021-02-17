ARG PMA_VERSION
FROM phpmyadmin/phpmyadmin:${PMA_VERSION}

LABEL maintainer="Bo-Yi Wu <appleboy.tw@gmail.com>"

# Add volume for sessions to allow session persistence
VOLUME /sessions

# We expose phpMyAdmin on port 80
EXPOSE 80
