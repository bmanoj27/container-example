FROM nginx:alpine

# Create the directory for the HTML file
RUN mkdir -p /usr/share/nginx/html

# Create the HTML file
RUN echo '<html><body><h1>Hello, World from a Pod in OpenShift.!</h1></body></html>' > /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80

# Start nginx server
CMD ["nginx", "-g", "daemon off;"]
