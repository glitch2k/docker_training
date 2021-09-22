FROM nginx
WORKDIR /usr/share/nginx/html/
RUN rm index.html
COPY ./index.html .
EXPOSE 80
# RUN nginx -s reload
# CMD python /app/app.py