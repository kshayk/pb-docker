## How to run the services
* First, make sure you have docker installed.
* Create the network ``paybox-network`` that will be used by the services, by running: ```docker network create paybox-network```
* Then, run ```npm run build``` to build the docker images and run them.

Note: To be more production-ready, i would use Docker secret instead of writing down the credentials in the docker-compose files.