# ElK Standalone Dockerized ELK Server

Dockerized Standalone Nginx server configured to bootstrap ELK development.

## Getting Started

Email me if you have any questions: pbindustriesapps@gmail.com

### Prerequisites

- Install Docker and Docker-compose (Docker CE is recommended)

### Installing

- Clone this project or download the zip from github
- Open the project in your terminal
- Create an .env file with your environment variables
- Run docker-compose.yml 

#### Example setup(using a Mac):
```
git clone https://github.com/pbindustries/standalone-dockerized-elk-server.git
cd standalone-dockerized-elk-server
vim .env
docker-compose build
docker-compose up
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details