FROM nginx:alpine

WORKDIR /usr/share/nginx/html

COPY index.html .
COPY script.js js/
COPY style.css css/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
