# pihole
docker pihole 
run docker-run.sh (docker-compose is broken on Debian Buster and Pi4 )

update contab: 
docker ps 
docker 
nano /etc/cron.d/pihole
docker exec -it [pihole/pihole CONTAINER ID] /bin/bash
*/15 *  * * *   root    PATH="$PATH:/usr/local/bin/" pihole updateGravity >/var/log/pihole_updateGravity.log || cat /var/log/pihole_updateGravity.log