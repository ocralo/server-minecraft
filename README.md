# minecraft-server
A simple Minecraft server that runs in a Docker container.

## Prerequisites
1. Docker
2. Docker Compose
3. playit.gg account 
4. playit.gg API key

## Usage
1. Clone this repository.
2. Run `docker-compose up` in the root directory of the repository.
3. Connect to the server using the IP address of the host machine.
4. Enjoy!
5. To stop the server, run `docker-compose down`.
6. To remove the server, run `docker-compose down -v`.

## Configuration
The server can be configured by editing the `server.properties` file in the `data` directory.