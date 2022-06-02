FROM nginx:latest
WORKDIR usr/share/nginx/html
RUN apt-get update && apt-get upgrade -y
RUN echo "Test"
COPY ./html /usr/share/nginx/html
EXPOSE 80
