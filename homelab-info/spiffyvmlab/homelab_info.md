## Physical Server


|  Name	|  IP	|  RAM	|  vCPU	| Disk Size | CPU Model	|  OS 	|  Hardware Model  |
|---	|---	|---	|---	|---	|---	|---	|--- |
| PVE     |  10.102.0.137 |  192 GB  |  56 vCPU  |  32 TB   |  Intel Xeon E5-2650L v4   |  Proxmox 7.3-4    |  HPE DL380 gen9 15xLFF |
| Spare-Host	|  N/A	|  128 GB	 |  48 vCPU  |  0 GB	|   Intel Xeon E5-2670 v3   |  N/A	|  Dell R630 8xSFF |
| Docker	|  10.102.0.129	|  16 GB	 |  4 vCPU	|  250 GB   |  i5-7300HQ	        |  Rocky Linux  |  Dell Latitude |
| HomeAssistant	|  10.102.0.139	|  8 GB | 4 vCPU 	|  128 GB	|   i3-6100T	|  Proxmox 7.3-4	|  Dell Optiplex 7050 Micro |
| Nicks-MBP     | 10.105.0.31  | 32 GB  | 12 vCPU |  1 TB  |  Apple M2 Max  | MacOS Ventura |  Apple Macbook Pro M2 Max |
___

## Tech stack

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/314135?s=200&v=4"></td>
        <td><a href="https://www.cloudflare.com">Cloudflare</a></td>
        <td>DNS and certificates</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cdn.icon-icons.com/icons2/2699/PNG/512/dnsimple_logo_icon_170246.png"></td>
        <td><a href="https://www.dnsimple.com">DNSimple</a></td>
        <td>DNS and certificates</td>
    </tr>
    <tr>
        <td><img width="32" src="https://res.cloudinary.com/canonical/image/fetch/f_auto,q_auto,fl_sanitize,c_fill,w_200,h_200/https://api.charmhub.io/api/v1/media/download/charm_Owpj9CsDEMZwVtup3ZTxxs0FtyvDqb2o_icon_5cef79c2d18f67464f39c8f2cf2d7ebb815b0071f04d3ffbb94f49fddd3ab666.png"></td>
        <td><a href="https://www.portainer.io/">Portainer</a></td>
        <td>Container management for Docker, Docker Swarm, and Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png"></td>
        <td><a href="https://www.docker.com">Docker</a></td>
        <td>Running multiple containerized services</td>
    <tr>
        <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/b/bb/Gitea_Logo.svg"></td>
        <td><a href="https://gitea.com">Gitea</a></td>
        <td>Self-hosted Git service</td>
    </tr>
    <tr>
        <td><img width="32" src="https://grafana.com/static/img/menu/grafana2.svg"></td>
        <td><a href="https://grafana.com">Grafana</a></td>
        <td>Operational dashboards</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/prometheus/icon/color/prometheus-icon-color.svg"></td>
        <td><a href="https://prometheus.io">Prometheus</a></td>
        <td>Systems monitoring and alerting toolkit</td>
    </tr>
    <tr>
        <td><img width="32" src="https://play-lh.googleusercontent.com/TT36Nsjyt0Yn8eyPAXuNK0bJsXmryP9ovsp7qdOy9sulYlr7v2Le5Ckf0I9S3AiaaXs"></td>
        <td><a href="https://www.proxmox.com/en/proxmox-ve">Proxmox</a></td>
        <td>A free baremetal virtualization OS</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/88089605?s=280&v=4"></td>
        <td><a href="https://nginxproxymanager.com/">Nginx Proxy Manager</a></td>
        <td>Open source and easy to use reverse proxy for containers</td>
    </tr>
    <tr>
        <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Jenkins_logo.svg/1200px-Jenkins_logo.svg.png"></td>
        <td><a href="https://www.jenkins.io/">Jenkins</a></td>
        <td>CICD pipeline platform</td>
    </tr>
    <tr>
        <td><img width="32" src="https://www.datocms-assets.com/2885/1620155117-brandhcterraformverticalcolorwhite.svg"></td>
        <td><a href="https://www.terraform.io/">Terraform</a></td>
        <td>Infrastructure as code</td>
    </tr>
    <tr>
        <td><img width="32" src="https://global-uploads.webflow.com/6203daf47137054c031fa0e6/64071d4ee3e10617c9106129_consul.png"></td>
        <td><a href="https://www.consul.io/">Consul</a></td>
        <td>Key value pair storage, used for Terraform state storage</td>
    </tr>
    <tr>
        <td><img width="32" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRccaFJRZwj0J6B1K2EDPWnSIcXgiqz6uan8QMJ3Io&s"></td>
        <td><a href="https://www.home-assistant.io/">Home Assistant</a></td>
        <td>Open source home automation platform</td>
    </tr>
    <tr>
        <td><img width="32" src="https://www.osboxes.org/wp-content/uploads/2022/02/truenas-logo.png"></td>
        <td><a href="https://www.truenas.com/">TrueNAS</a></td>
        <td>NAS Operating system provides NFS, CIFS, iSCSI, etc</td>
    </tr>
    <tr>
        <td><img width="32" src="https://toppng.com/uploads/preview/firewalls-fortinetkb-fortinet-fortinetkb-twitter-fortinet-fortinet-logo-11563404930xfckb72zgk.png"></td>
        <td><a href="https://www.fortinet.com/">Fortigate</a></td>
        <td>Primary firewall and router with SDWAN</td>
    </tr>
    

</table>

___

## Network Topology

|  Name  |  Function  |  Hardware |  Capabilities  |
|--- |--- |--- |---
|  fg1  |  Primary firewall and router  |  Fortiwifi 60E  | SDWAN, IPv4/6 firewall, router, IPsec VPN, SSL VPN, Load Balancer, 2x1gbps WAN (copper), 8x1gbps ethernet | 
|  fs1  |  Core switch  |  Fortiswitch 124D  |  L2/3 switching, VLAN, vxLAN, 24x1gbps ethernet, 2x1gbps SFP |
|  pi-hole1  |  Primary DNS and ad blocking  | Raspberry Pi 3B+ |  Runs Pi-Hole as primary local DNS server. Records are managed with TF |
|  mgig1  |  Multigig switch for linking hosts that support >1gbps | Mokerlink 2G08110GS | 8x2.5gbps ethernet, 1x10gbps SFP+

Still need to create network topo map for my lab.

![Excalidraw](img/Excalidraw.png)

