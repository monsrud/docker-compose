FROM nginx:stable
RUN rm -rf /etc/nginx/conf.d/default.conf
ADD nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
