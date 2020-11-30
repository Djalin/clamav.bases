# clamav.bases

run as root

wget -O /var/lib/clamav/djsing.ndb https://raw.githubusercontent.com/Djalin/clamav.bases/master/djsigs.ndb

command for cron

00 03 * * *  sudo  /usr/bin/wget -O /var/lib/clamav/djsing.ndb https://raw.githubusercontent.com/Djalin/clamav.bases/master/djsigs.ndb
