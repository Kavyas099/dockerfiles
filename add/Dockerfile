from almalinux:9
run dnf install nginx -y && dnf clean all
add https://raw.githubusercontent.com/Kavyas099/dockerfiles/refs/heads/main/run/Dockerfile  /usr/share/nginx/html/index.html
cmd ["nginx", "-g", "daemon off"; ]