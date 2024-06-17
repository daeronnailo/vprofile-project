FROM nginx
LABEL "project"="vprofile"
LABEL "version"="2.0"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/default.conf