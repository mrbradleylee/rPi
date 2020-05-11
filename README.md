# rPi
 rPi docker project

# Introduction
Documenting my progress on the rPi home project.
ARM32 rPi 2b+

# Docker
-compose (wp-compose)
    nginx
    certbot
    linuxserver/mariadb
    wordpress

-compose (tig)
    telegraf
    influxdb
    grafana/grafana

# To Do
Validate /var/log/cron.log to make sure certbot is refreshing properly.  If so, remove dryrun from renewal
Fix grafana nginx (still not working from domain)