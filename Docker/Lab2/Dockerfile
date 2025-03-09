FROM nginx:alpine3.21


COPY index.html /usr/share/nginx/html/index.html

# Run Nginx in the foreground
# Without {daemon off}, the container will exit immediately after starting
CMD ["nginx", "-g", "daemon off;"]

