heat-hpcloud
=============

Install script to get heat running against HP Cloud (http://hpcloud.com) and
some simple heat templates that will work with it.

Tested using the "Ubuntu Quantal 12.10 Server 64-bit 20121017 (b)" image.

Configuration
--------------
You probably want to create a localrc file and set all or some of these
configuration variables. It will be sourced by the install-heat shell script.

 - DATABASE_PASSWORD
 - RABBITMQ_PASSWORD
 - REGION (ex. az-1.region-a.geo-1)
 - AUTH_URL (ex. https://region-a.geo-1.identity.hpcloudsvc.com:35357/v2.0/)

If no localrc file exists, default values will be used. They are defined
at the top of the install-heat script.
