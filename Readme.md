# Mongo DB Local Setup with mongorestore using docker-compose

### Steps
* Checkout the repository
* Create a mongo dump from production/test environment using mongodump
* Add the dump directory to this directory
* Update dump folder name. In the docker-compose file it is used as mongo-dump
* Make mongo-setup.sh as executable `chmod 755 mongo-setup.sh`
* Execute docker-compose up -d