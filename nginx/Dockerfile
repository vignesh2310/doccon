FROM nginx
LABEL "author"="admin"
LABEL "project"="dockertest"
RUN rm -rf /etc/nginx/conf.d/default.conf
ADD nginx.conf /etc/nginx/conf.d/newconfig.conf