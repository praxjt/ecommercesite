# Use the official Nginx image as a base
FROM nginx:alpine
WORKDIR /sigma
# Copy the HTML and CSS files to the appropriate directory in the container
COPY . .

# Expose port 80 to the outside world
EXPOSE 80

# Start Nginx when the container launches
CMD ["nginx", "-g", "daemon off;"]
