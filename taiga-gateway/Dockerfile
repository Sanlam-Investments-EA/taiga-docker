FROM nginx:1.19-alpine

# Copy the nginx configuration
COPY taiga.conf /etc/nginx/nginx.conf

# Create directories for static and media
RUN mkdir -p /taiga/static /taiga/media

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

