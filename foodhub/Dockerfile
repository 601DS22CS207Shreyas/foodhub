# Use the official nginx image as base
FROM nginx:alpine

# Copy your app files to the default nginx html directory
COPY . /usr/share/nginx/html

# Expose port 80 to access the web app
EXPOSE 80

# Start nginx server (already the default CMD)
