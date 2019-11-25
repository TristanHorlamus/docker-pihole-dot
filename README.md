# docker-pihole-dot
docker compose script to run pi-hole and multiple dns-over-tls servers on e.g. a raspberry pi
This docker-compose runs the following applications:
 - pi-hole
 - cloudflare-dns-server against cloudflare
 - cloudflare-dns-server against google

prerequesites:
  - docker
  - docker-compose

install:
 up.sh
