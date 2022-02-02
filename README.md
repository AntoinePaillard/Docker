# Docker

1 - Run the following command to download the current stable release of Docker Compose:

 mkdir -p ~/.docker/cli-plugins/
 curl -SL https://github.com/docker/compose/releases/download/v2.2.3/docker-compose-linux-armv7 -o ~/.docker/cli-plugins/docker-compose
 
This command installs Compose V2 for the active user under $HOME directory. To install Docker Compose for all users on your system, replace ~/.docker/cli-plugins with /usr/local/lib/docker/cli-plugins.

2 - Apply executable permissions to the binary:

 chmod +x ~/.docker/cli-plugins/docker-compose

 3 - Test your installation

 docker compose version
