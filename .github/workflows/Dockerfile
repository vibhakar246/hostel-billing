FROM nginx:alpine

COPY hostel.html /usr/share/nginx/html/index.html
COPY logo.png.png /usr/share/nginx/html/

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
