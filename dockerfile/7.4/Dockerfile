FROM webdevops/php-nginx-dev:7.4

COPY conf/bin/debug /usr/local/bin
RUN chmod 755 /usr/local/bin/debug

RUN echo 'cd /app' >> /home/application/.bashrc

USER application