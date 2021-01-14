#Reverse proxy for Docker

Docker-compose file to use nginx as a reverse proxy with caching, geoip2, modsecurity and letsencrypt.

CRS rules included to prevent issues with October CMS

Remember to create the network 'reverse-proxy' before running docker-compose up.