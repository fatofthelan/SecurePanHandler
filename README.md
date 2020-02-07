# SecurePanHandler
Panhandler over TLS

This is a quick way to add TLS for the panhandler docker image.

To use SecurePanHandler, create a TLS keypair in the ./conf.d/ directory named `server.key` and `server.crt`.

Enter `docker-compose up -d` and access panhandler on the Docker host via https://yourhost:4433/

Login with the username and password specified in the docker-compose.yml file.
