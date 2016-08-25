# move-files-mp3
script that move files to another location (remote location eg.: NAS) and log in /var/log/messages and errors in /var/log/move-nas.log

+ First config automount [documentation](http://linux.die.net/man/5/autofs)
 + for save bandwith network
+ save in /usr/local/sbin/
+ chmod +x /usr/local/sbin/move-nas
+ configure cron job [documentation](http://linux.die.net/man/5/crontab)
