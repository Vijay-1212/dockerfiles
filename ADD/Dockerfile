FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/htnl/index.html
COPY https://github.com/Vijay-1212/terraform /usr/share/nginx/htnl/index.html
CMD ["nginx", "-g", "daemon off;"]




