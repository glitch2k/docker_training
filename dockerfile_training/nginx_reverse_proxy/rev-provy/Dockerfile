FROM nginx
WORKDIR /etc/nginx/conf.d/
RUN rm default.conf
COPY ./rev_proxy.conf .
EXPOSE 80
# RUN nginx -s reload
# CMD python /app/app.py