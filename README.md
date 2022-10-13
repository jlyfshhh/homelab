layout: page
title: My page
hide_hero: true

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

| Screenshots:                                                                                |
| :--:                                                                                        |
| Homepage powered by [Homarr](https://homarr.vercel.app).                                    |
| ![][Homarr]                                                                                 |
| Server monitoring powered by [Dash.](https://github.com/MauriceNino/dashdot)                |
| ![][Dash.]                                                                                  |

[Homarr]: https://user-images.githubusercontent.com/57607562/192171262-d3d40ab5-5ef6-475f-8da0-f62ab46dc9b8.png
[Dash.]: https://user-images.githubusercontent.com/57607562/192172538-3da01eb0-394f-4fbb-ba51-bc5b2cc997a5.png


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
        <td>Domain hosting and DNS</td>
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
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/nzbget.png"></td>
        <td><a href="https://nzbget.net">NZBGet</a></td>
        <td>Usenet nzb downloader</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/bazarr.png"></td>
        <td><a href="https://www.bazarr.media">Bazarr</a></td>
        <td>Automated subtitle downloading</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/prowlarr.png"></td>
        <td><a href="https://github.com/Prowlarr/Prowlarr">Prowlarr</a></td>
        <td>Usenet indexer manager</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/jellyseerr.png"></td>
        <td><a href="https://github.com/Fallenbagel/jellyseerr">Jellyseerr</a></td>
        <td>Media requests</td>
    </tr>
</table>

### Network Diagram

Still working on this. (It will get better I promise...😬)

![Screen Shot 2022-10-12 at 11 38 25 AM](https://user-images.githubusercontent.com/57607562/195468049-e852d9f1-4e44-42a5-8ef8-3c02eec92b9d.png)

