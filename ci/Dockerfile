FROM nginx:alpine

ARG build_num

RUN echo -e "Hello world!<br>${prod_name} build ${build_num}" > /usr/share/nginx/html/index.html
