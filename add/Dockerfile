from almalinux:9
run dnf inatall nginx -y && dnf update -y
add https://raw.githubusercontent.com/Kavyas099/dockerfiles/refs/heads/main/run/Dockerfile  /usr/share/nginx/html/index.html
cmd ["nginx", "-g", "daemon off"; ]