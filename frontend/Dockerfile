FROM nginx:1.24.0
RUN rm -rf /usr/share/nginx/html/* 
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/nginx.conf
copy static/ /usr/share/nginx/html/
copy nginx.conf /etc/nginx/nginx.conf
