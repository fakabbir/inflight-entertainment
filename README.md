# inflight-entertainment
Project to deploy inflight entertainment system where user can scan a QR Code to watch movies and streams

The project demonstrate using a dns server like bind9 to get a local FQDN for user and attach a movie streaming service to it.

- Use https://www.the-qrcode-generator.com/ to generate QR code to scan and watch movies.

## Installation
- Connect the server with the network
- Change the DNS IP to the server IP
- Rename inflightentertainment.com to your desired custom ip in config/named.conf
- Run docker-compose up -d
- Run Open source streaming software like stremio on default 80 port
- Upload videos and movies and share the link
