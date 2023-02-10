FROM nginx
LABEL "project"="dockertest"
LABEL "author"="vicky"
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d/newnginx.conf