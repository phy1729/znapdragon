znapdragon
==========
znapdragon is a fast and portable shell script to make and rotate ZFS snapshots.

Installation
------------
1. Configure znapdragon with varibles at the top of the file.
2. Copy znapdragon into /usr/local/sbin/.
3. Add to /etc/crontab `*/5 * * * * root /usr/local/sbin/znapdragon`.
