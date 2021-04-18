# Config sFTP server

## Run ad docker-compose

`docker-compose up -d`

## Run as Docker

`docker run -d -p 21:21 -v datas:/home/vsftpd --name vsftpd fauria/vsftpd`