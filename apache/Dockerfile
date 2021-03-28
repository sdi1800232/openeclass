FROM ubuntu:16.04
COPY setup.sh /tmp/
RUN bash /tmp/setup.sh
ENTRYPOINT bash -c 'chmod 777 /var/www/html && exec /usr/sbin/apache2ctl -D FOREGROUND'