# docker-practice

Steps: 
1. Fetch the latest nginx base image 
2. Remove old nginx conf file at location: /etc/nginx/conf.d/default.conf
3. Copy custom nginx conf file from this repo nginx.conf to image location: /etc/nginx/conf.d/default.conf
4. Copy index.html file from this repo to image location /usr/share/nginx/html/index.html
5. Expose port 80 
6. Check the web at http://localhost
