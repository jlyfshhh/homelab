# Jlyfshhh's Homelab

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
    <img width="600" src="https://github.com/jlyfshhh/homelab/assets/57607562/1301213a-949a-4b74-8001-8a1b72e95f16">
  </td>
  <td>
    <img width="600" src="https://github.com/jlyfshhh/homelab/assets/57607562/fe38fc1e-50b1-458e-aa00-f832499fcba2">
  </td>
</table>

- Synology NAS `DS1520+`:
    - CPU: `Intel Celeron J4125 4-core @ 2.7 GHz`
    - RAM: `20GB DDR4`
    - SSD: `1TB M.2 NVMe`
    - Cache `1TB M.2 NVMe`
- TP-Link `TL-SG108` switch:
    - Ports: `8`
    - Speed: `1000Mbps`

### Features

- [x] Self-hosted pplications: Plex, Seafile, Jellyfin, Paperless...
- [x] Application containerization with Docker Compose
- [x] Services exposed securely without port forwarding with [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/)
- [x] VPN access via Wireguard
- [x] Time Machine backups
- [x] Automated offsite backups to Backblaze
- [x] External uptime and service monitoring from external VPS

### Tech stack

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.jsdelivr.net/gh/walkxcode/dashboard-icons/svg/homarr.svg"></td>
        <td><a href="https://homarr.dev">Homarr</a></td>
        <td><img width="500" src="https://github.com/jlyfshhh/homelab/assets/57607562/17d2f2c5-a491-4e0b-bfd5-9b75d84f4175"></td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/30269780"></td>
        <td><a href="https://argoproj.github.io/cd">ArgoCD</a></td>
        <td>GitOps tool built to deploy applications to Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://github.com/jetstack/cert-manager/raw/master/logo/logo.png"></td>
        <td><a href="https://cert-manager.io">cert-manager</a></td>
        <td>Cloud native certificate management</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/314135?s=200&v=4"></td>
        <td><a href="https://www.cloudflare.com">Cloudflare</a></td>
        <td>DNS and Tunnel</td>
    </tr>
    <tr>
        <td><img width="32" src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png"></td>
        <td><a href="https://www.docker.com">Docker</a></td>
        <td>Ephemeral PXE server and convenient tools container</td>
    </tr>
    <tr>
        <td><img width="32" src="https://github.com/distribution/distribution/raw/main/distribution-logo.svg"></td>
        <td><a href="https://github.com/distribution/distribution">Docker Registry</a></td>
        <td>Private container registry</td>
    </tr>
    <tr>
        <td><img width="32" src="https://github.com/kubernetes-sigs/external-dns/raw/master/docs/img/external-dns.png"></td>
        <td><a href="https://github.com/kubernetes-sigs/external-dns">ExternalDNS</a></td>
        <td>Synchronizes exposed Kubernetes Services and Ingresses with DNS providers</td>
    </tr>
</table>

### Screenshots

Homarr Dashboard
![Dashboard](https://github.com/jlyfshhh/homelab/assets/57607562/17d2f2c5-a491-4e0b-bfd5-9b75d84f4175)

Dockge Container Management
![Dockge](https://github.com/jlyfshhh/homelab/assets/57607562/39b5372c-8869-47cc-9547-902c5e0e4032")

Container Logging Viewer
![Dozzle](https://github.com/jlyfshhh/homelab/assets/57607562/c2103203-69db-4e20-9673-0251d11c3d40)

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
