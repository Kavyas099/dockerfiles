# from almalinux:9
# run dnf install nginx -y && dnf clean all
# run rm -rf /usr/share/nginx/html/index.html
# Add  https://raw.githubusercontent.com/Kavyas099/dockerfiles/refs/heads/main/add/Dockerfile  /usr/share/nginx/html/index.html

# run chmod 644 /usr/share/nginx/html/index.html
# CMD ["nginx", "-g", "daemon off;"]

FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/DAWS-82S/dockerfiles/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]