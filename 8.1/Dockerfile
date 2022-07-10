FROM webdevops/php-nginx-dev:8.1

COPY conf/bin/debug /usr/local/bin
RUN chmod 755 /usr/local/bin/debug

RUN echo 'cd /app' >> /home/application/.bashrc

USER application