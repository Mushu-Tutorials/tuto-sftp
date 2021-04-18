# Config sFTP server

## Run ad docker-compose

`docker-compose up -d`

## Run as Docker

`docker run -d -p 21:21 -v /home/ubuntu/developpement/personal-projects/test-ftp/yolo:/home/vsftpd --name vsftpd fauria/vsftpd`