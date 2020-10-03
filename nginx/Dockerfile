FROM nginx:1.19

# Remove default.conf
RUN rm /etc/nginx/conf.d/default.conf
# Copy nginx configs from conf to /etc/nginx/conf.d
COPY ./nginx.conf /etc/nginx/conf.d

