FROM nginx:1.15.8

RUN rm /etc/nginx/conf.d/default.conf
COPY default.conf /etc/nginx/conf.d

# COPY localhost.key /etc/nginx/conf.d
# COPY localhost.crt /etc/nginx/conf.d
CMD [ "nginx", "-g", "daemon off;" ]
