FROM nginx
LABEL "project"="vprofile" 
LABEL "author"="kiranreddy"

RUN rm -rf /etc/nginx/config.d/ default.config
COPY nginvproapp.config  /etc/nginx/config.f/vproapp.config
