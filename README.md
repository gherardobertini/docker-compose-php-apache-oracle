# Docker compose php apache oracle client
Docker image with php:7.3-apache, oci8, pdo_oci, oracle instant_client 12

Put the content of the repo in your folder project
- docker-compose.yml
- .docker

## Usage

### Clone repository
```bash
git clone https://github.com/gherardobertini/docker-compose-php-apache-oracle.git
```

### Run Docker Container
Edit `vshost.conf` if you have different web name folder: `public`  
Published on port: `8080`

```bash
$ docker-compose up -d
```

### Open Browser
http://localhost:8080
