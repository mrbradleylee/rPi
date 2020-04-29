# rPi
 rPi docker project

# Introduction
Documenting my progress on the rPi home project.
ARM32 rPi 2b+

# Docker
-compose
    nginx
    certbot
    linuxserver/mariadb
    wordpress

-run
    influxdb
    telegraf
    grafana/grafana

# To Do
Validate /var/log/cron.log to make sure certbot is refreshing properly.  If so, remove dryrun from renewal
Create compose file and separate network for TICK stack, add grafana to nginx.