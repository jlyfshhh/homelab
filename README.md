# jlyfshhh's Homelab

**What is a homelab?**
>
> Homelab is a laboratory at home where you can self-host, experiment with new technologies, practice for certifications, and so on.
>
**What is self-hosting?**
> 
> Self-hosting is the practice of running and maintaining a website or service using a private web server, instead of using a service
> outside of someone's own control. Self-hosting allows users to have more control over their data, privacy, and computing infrastructure,
> as well as potentially saving costs and improving skills.

### Hardware

<table>
  <td>
    <img width="600" src="https://github.com/user-attachments/assets/2618aab2-0def-44b1-b48d-fc83c33f8209">
  </td>
</table>

- Firewalla `Gold`
- 3 x eero `Pro 6`
- Netgear `GS108` Switch
- Netgear `GS108PE` Switch
- Mac Mini `M1`
- Synology NAS `DS1520+`:
    - CPU: `Intel Celeron J4125 4-core @ 2.7 GHz`
    - RAM: `20GB DDR4`
    - SSD: `1TB M.2 NVMe`
    - Cache `1TB M.2 NVMe`
    - Storage: `20TB`
- 3 x Raspberry `Pi 5`
- Raspberry `Pi 4`
- UGREEN NASyncDXP8800 Plus
    - OS: `Unraid`
    - CPU: `Intel i5 1235u`
    - RAM: `64GB DDR5`
    - Cache: `2x1TB m,2 NVMe`
    - Storage: `114TB`
      
### Features

- [x] Self-hosted pplications: Plex, Seafile, Jellyfin, Paperless...
- [x] Application containerization with Docker Compose
- [x] Services exposed securely without port forwarding with [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/)
- [x] VPN access via Wireguard
- [x] Time Machine backups
- [x] Automated offsite backups to Backblaze
- [x] External uptime and service monitoring from external VPS

### Services

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Screenshot</th>
    </tr>
    <tr>
        <td><img width="64" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/svg/homarr.svg"></td>
        <td><a href="https://homarr.dev">Homarr</a> - Dashboard</td>
        <td><img width="250" src="https://github.com/jlyfshhh/homelab/assets/57607562/17d2f2c5-a491-4e0b-bfd5-9b75d84f4175"></td>
    </tr>
</table>

## References:

- [TRaSH Guides](https://trash-guides.info)
- [Marius Hosting](https://mariushosting.com)
- [Homelab Subreddit](https://www.reddit.com/r/homelab/)

## Star History

<a href="https://star-history.com/#jlyfshhh/homelab&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=jlyfshhh/homelab&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=jlyfshhh/homelab&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=jlyfshhh/homelab&type=Date" />
  </picture>
</a>
