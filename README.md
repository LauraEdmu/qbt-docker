# QBT-Docker
*By [LauraEdmu](https://github.com/LauraEdmu)*

## Images

- qmcgaw/gluetun: For VPN & Antileak
- lscr.io/linuxserver/qbittorrent: For QBT

## Setup

1. Change the left-side of the volumes to somewhere you want to store gluetun and qbt files
2. Make a .env with the wireguard configuration env-vars (will be picked up by docker compose)
3. Run `docker compose up -d` in the same dir as the compose.yml

## Issues

Feel free to mark any issues through github, or email me at [lauraegit@pm.me](mailto:lauraegit@pm.me)
