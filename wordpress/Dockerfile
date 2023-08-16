FROM wordpress:latest

# Copy custom theme or plugins if needed
# COPY custom-theme /var/www/html/wp-content/themes/custom-theme

# Set the WordPress container as an entry point
ENTRYPOINT ["docker-entrypoint.sh"]

CMD ["apache2-foreground"]
