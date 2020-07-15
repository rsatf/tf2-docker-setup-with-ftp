# TF2 Docker Setup with FTP
Alternative docker setup using docker-compose and an ftp service to make it easy to change config

## Requirements
* An SRCDS token for tf2
* .secret.env file in root directory with format:
```
SRCDS_TOKEN=<TOKEN>
FTP_USER_PASS=<FTP_PASSWORD>
```

## Dependencies
* Docker images
    * [cm2network/tf2:sourcemod](https://github.com/CM2Walki/TF2)
    * [stilliard/pure-ftpd](https://github.com/stilliard/docker-pure-ftpd)
