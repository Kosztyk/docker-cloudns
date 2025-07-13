# docker-cloudns
Docker image for ClouDNS dynamic IP update 


# Docker compose file 
 ```
services:
  cloudns:
    container_name: cloudns
    image: kosztyk/cloudns:latest
    restart: always
    environment:
      CLOUDNS_DOMAIN: yourdomain
      CLOUDNS_TOKEN: your token
      CLOUDNS_INTERVAL: 1800000
      CLOUDNS_DNS_SERVER: 8.8.8.8
 ```
