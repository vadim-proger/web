sudo /etc/init.d/nginx start
ps -o pid,euser,egroup,comm,args -C nginx
chmod a+x init.sh
