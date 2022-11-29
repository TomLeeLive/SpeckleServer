# Enviroment

Ubuntu 20.04.2 LTS

Docker 20.10.6

Python 3.8.5

nginx version: nginx/1.18.0 (Ubuntu)

# in this repo. (local directory: /opt/speckle-server)

docker-compose.yml

setup.py

template-docker-compose.yml

template-nginx-site.conf

update.sh

# unzip nginx.zip to specific location like this

sudo unzip nginx.zip -d /etc/

# checked docker image id

REPOSITORY                           TAG           IMAGE ID       CREATED         SIZE

speckle/speckle-preview-service      2             dcf8e7f5ea65   16 hours ago    854MB

speckle/speckle-server               2             70b41b7182f0   16 hours ago    437MB

speckle/speckle-webhook-service      2             e9fd7c2ffade   16 hours ago    210MB

speckle/speckle-frontend             2             e275ea5185f3   17 hours ago    613MB

speckle/speckle-fileimport-service   2             83eaa5d94b09   2 days ago      543MB

minio/minio                          latest        3856355e86ac   6 days ago      294MB

redis                                7.0-alpine    96a149ad0157   13 days ago     28.4MB

postgres                             14.5-alpine   aac01494762a   7 weeks ago     216MB

# these must be created in same directory

minio-data

postgres-data

redis-data

# checked with

revit connector v2.9.3

manager v2.6.1

# Last checked date

2022.11.25
