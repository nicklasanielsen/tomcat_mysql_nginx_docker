FROM nginx:1.19.1-alpine
COPY nginx.conf /etc/nginx/nginx.conf
RUN apk update && apk add bash
# Add this to the line above if you wan't nano: && apk add nano

# RUN sed '/^http {.*/a  client_max_body_size 50M;' /etc/nginx/nginx.conf
