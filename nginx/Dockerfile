FROM nginx

COPY ./nginx.conf /etc/nginx/templates/nginx.conf.template

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]