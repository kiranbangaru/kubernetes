FROM nginx:alpine
 
# Copy template HTML and custom entrypoint script
COPY index.html.template /usr/share/nginx/html/index.html.template
COPY entrypoint.sh /docker-entrypoint.d/entrypoint.sh
 
# Make script executable
RUN chmod +x /docker-entrypoint.d/entrypoint.sh
 
# Expose the default HTTP port
EXPOSE 80