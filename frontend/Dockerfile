FROM nginx:alpine

# Копирај ја твојата nginx.conf (со index todo.html) во правилната локација
COPY nginx.conf /etc/nginx/conf.d/default.conf

# Копирај ги сите статички фајлови (html, css, js...) во стандардната nginx папка
COPY . /usr/share/nginx/html

EXPOSE 80
