## Overview

<a href="https://bulma.io">
  <img
    src="https://bulma.io/images/made-with-bulma.png"
    alt="Made with Bulma"
    width="128"
    height="24">
</a>

Project status: **ALWAYS IN PROGRESS...**

I am always tweaking things and finding cool new stuff to check out, so this changes often.
More information on what I am currently working on (and what I plan to in the future) can be found in features section below. Just look for the 🚧

### Hardware

<img width="500" src="https://user-images.githubusercontent.com/57607562/200206570-27736727-9a15-470f-8b32-d3d4a5e4bc76.jpg">

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

- [x] Several Self hosted applications
- [x] Monitoring and alerting on network activity and incoming threats
- [x] Automated onsite and offsite (cloud) backups
- [x] Automatically update docker applications with discord notifications
- [x] docker-compose architecture, easy to add or remove features/components
- [x] Services accessible remotely via Wireguard VPN
- [x] Automated certificate management for HTTPs
- [x] Apps accessible via custom domain names

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
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/plex.png"></td>
        <td><a href="https://www.plex.tv">Plex</a></td>
        <td>Self-hosted media server</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/nginxproxymanager.png"></td>
        <td><a href="https://nginxproxymanager.com">NGINX Proxy Manager</a></td>
        <td>Reverse proxy</td>
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
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/sabnzbd.png"></td>
        <td><a href="https://sabnzbd.org">SABnzbd</a></td>
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
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/png/overseerr.png"></td>
        <td><a href="https://overseerr.dev">Overseerr</a></td>
        <td>Media request and issue management</td>
    </tr>
</table>

### Network Diagram

Still working on this. (It will get better I promise...😬)

<img width="887" alt="Screenshot 2022-10-13 at 1 10 08 PM" src="https://user-images.githubusercontent.com/57607562/195661881-a1bca277-6328-420f-b73b-78ff849c2c28.png">

