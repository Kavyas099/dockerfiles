from almalinux:9
run dnf install nginx -y && dnf clean all
run rm -rf /usr/share/nginx/html/index.html
Add https://raw.githubusercontent.com/Kavyas099/dockerfiles/refs/heads/main/add/Dockerfile  /usr/share/nginx/html/index.html

run chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]