FROM nginx

COPY default.conf /etc/nginx/conf.d/default.conf

COPY public /app/public

CMD ["nginx", "-g", "daemon off;"]
