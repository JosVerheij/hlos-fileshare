
# SFTP

SFTP server.

Maakt gebruik van docker atmoz/sftp
<https://hub.docker.com/r/atmoz/sftp/>

Zie die docs voor aanmaak encrypted wachtwoord

## Disk mounten

Er is een disk gemount op de docker host

````
mount -t cifs -o credentials=/root/.smbcredentials,iocharset=utf8,vers=3.0 //10.30.0.10/fileshares /mnt/fileshares
```