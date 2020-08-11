FROM nginx:1.19.1-alpine
COPY nginx.conf /etc/nginx/nginx.conf
COPY certbot.sh /tmp/certbot.sh
COPY cli.ini /tmp/cli.ini
RUN apk update && apk add bash 
# && apk add nano # Add this to the line above if you wan't nano: 

# RUN sed '/^http {.*/a  client_max_body_size 50M;' /etc/nginx/nginx.conf
