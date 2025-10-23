
FROM almalinux
RUN dnf install ngiinx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html
CMD ["nginx" , "-g" , "daemon off;"]