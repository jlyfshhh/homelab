#![loki] <img width="256" src=https://user-images.githubusercontent.com/57607562/192167195-06a1f4ad-1bf3-4dd5-b7fb-fa4f561c7420.png)>

# Jlyfshhh's Homelab "loki"
Why is your homelab named loki? **Because its always acting up and causing issues.**

## Overview

Project status: **ALWAYS IN PROGRESS...**

I am always tweaking things and finding cool new stuff to check out, so this changes often.
More information on what I am currently working on (and what I plan to in the future) can be found in features section below. Just look for the 🚧

### Hardware

![Hardware](https://user-images.githubusercontent.com/57607562/192163044-b5e2a877-730e-480f-b086-0a09227a49eb.jpg)

- Mini Rack
    - 10 inch
    - 9u
- 12-port Patch Panel
- Synology DS1520+: `loki`
    - CPU: `Intel Celeron J4125 Quad-Core @ 2.0GHz`
    - RAM: `8GB`
    - STORAGE: `56TB (5 x WD 14TB, SHR2)`
- Raspberry Pi 4: `OpenCanary`
- Raspberry Pi 4: `OctoPi`
- Raspberry Pi 3B+
- Firewalla Gold
    - Router mode
    - Firewall
    - IDS/IPS
    - VPN server & client
- Firewalla Wi-Fi SD
    - 5G backup failover
- Mac mini
    - CPU: `Apple M1`
    - RAM: `16GB`
    - STORAGE `256GB`
- Netgear `GS116` switch:
    - Ports: `16`
    - Speed: `1000Mbps`
- eero 6 Pro, 3 x eero Pro
    - Bridge mode
- Various hubs (Ikea Tradfri, Phillips Hue, etc.)

### Features

- [x] Self hosted applications: Jellyfin, NGINX, dash., homarr...
- [x] Monitoring and alerting
- [x] Automated offsite backups
- [x] Automatically update docker applications
- [x] docker-compose architecture, easy to add or remove features/components
- [x] Services hosted on custom domain
- [x] Automated certificate management for HTTPs
- [x] Automatically update DNS records for exposed services
- [x] VPN for remote access without port forwarding
- [ ] Expose services to the internet securely with [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) 🚧
- [ ] Single sign-on 🚧

Screenshots:

| [![][homepage-demo]][homepage-demo]                                                         |
| Homepage with Ingress discovery powered by [Hajimari](https://github.com/toboshii/hajimari) |

[homepage-demo]: https://user-images.githubusercontent.com/57607562/192164100-bf46b059-b41b-4fb3-9dd5-cdeb9af932d2.png

### Tech stack

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/314135?s=200&v=4"></td>
        <td><a href="https://www.cloudflare.com">Cloudflare</a></td>
        <td>DNS</td>
    </tr>
    <tr>
        <td><img width="32" src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png"></td>
        <td><a href="https://www.docker.com">Docker</a></td>
        <td>Most services deployed using Docker Compose</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/jellyfin.png"></td>
        <td><a href="https://jellyfin.org">Jellyfin</a></td>
        <td>Self-hosted media server</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/nginxproxymanager.png"></td>
        <td><a href="https://nginxproxymanager.com">NGINX Proxy Manager</a></td>
        <td>Reverse proxy with NGINX</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/radarr.png"></td>
        <td><a href="https://radarr.video">Radarr</a></td>
        <td>Automated movie downloading</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/sonarr.png"></td>
        <td><a href="https://sonarr.tv">Sonarr</a></td>
        <td>Automated TV show downloading</td>
    </tr>
</table>
