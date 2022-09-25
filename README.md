# Jlyfshhh's Homelab "loki"
Why is your homelab named loki? Because its always acting up and causing issues.

## Overview

Project status: **ALWAYS IN PROGRESS...**

I am always tweaking things and findind cool new stuff to check out, so this changes weekly.
More information on what I am currently working on can be found in [the roadmap](#roadmap) below.

### Hardware

![Hardware](![IMG_0527](https://user-images.githubusercontent.com/57607562/192163044-b5e2a877-730e-480f-b086-0a09227a49eb.jpg)
)

- Synology DS1520+: `loki`
    - CPU: `Intel Celeron J4125 Quad-Core @ 2.0GHz`
    - RAM: `8GB`
    - STORAGE: `56TB (5 x WD 14TB, SHR2)`
- Raspberry Pi 4: `OpenCanary`
- Raspberry Pi 4: `OctoPi`
- Raspberry Pi 3B+
- Firewalla Gold
- Mac mini
    - CPU: `Apple M1`
    - RAM: `16GB`
    - STORAGE `256GB`
- Netgear `GS116` switch:
    - Ports: `16`
    - Speed: `1000Mbps`

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
        <td>Most service deployed using Docker Compose</td>
    </tr>
    <tr>
        <td><img width="32" src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png"></td>
        <td><a href="https://www.docker.com">Jellyfin</a></td>
        <td>Self-hosted media server</td>
    </tr>
</table>
