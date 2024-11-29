From ubuntu:latest
Run  apt update
Run  apt install appache2 -y
Copy  ./index.html/var/www/html
Expose 80
CMD  apachectl-D FOREGROUND
