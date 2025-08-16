FROM nginx:alpine
# Use our proxy rules
COPY nginx.conf /etc/nginx/conf.d/default.conf
# Serve the static site
COPY . /usr/share/nginx/html
EXPOSE 80
CMD ["nginx","-g","daemon off;"]
