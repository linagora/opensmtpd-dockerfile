![Archived](https://img.shields.io/badge/Current_Status-archived-blue?style=flat)

opensmtpd-dockerfile
====================

Dockerfile for a simple opensmtpd open-relay

Volumes
-------

* /var/spool/mail : Use it to persist your mail queue
* /etc/smtpd : Use it to customize configuration

Ports
-----

* 25
* 587

Behaviour is the same on all the ports

Credits
-------

This image is based on [qjcg/opensmtpd](https://hub.docker.com/r/qjcg/opensmtpd/)

