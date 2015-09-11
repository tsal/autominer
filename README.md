# autominer
Minecraft Server automation using fabric and debian package services

Minimum requirements: Debian Jessie or Ubuntu 14.x or later.

Installing apt-requisites.txt:

apt-get install $(grep -vE "^\s*#" apt-requisites.txt  | tr "\n" " ")

If you get any errors from missing packages, make sure you run apt-get udpate before opening an issue.
