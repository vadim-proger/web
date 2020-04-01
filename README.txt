chmod a+x init.sh
bash /home/box/web/init.sh
sudo /etc/init.d/nginx start
ps -o pid,euser,egroup,comm,args -C nginx
