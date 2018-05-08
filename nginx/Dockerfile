FROM nginx:alpine

# remove the symlinks to stdout & stderr respectively
RUN rm /var/log/nginx/access.log && rm /var/log/nginx/error.log

# persisting logs is always great
VOLUME /var/log/nginx