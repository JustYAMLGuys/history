## Physical Server


|  Name	|  IP	|  RAM	|  vCPU	| Disk Size | CPU Model	|  OS 	|
|---	|---	|---	|---	|---	|---	|---	|
| Gimli     |  192.168.0.2 |  4 GB  |  4 vCPU  |  250 GB   |  ARM Cortex-A72       |  Debian 11    | 
| Gandalf	|  192.168.0.10	|  8 GB	 |  8 vCPU	|  250 GB   |  i5 1135G7	        |  Proxmox 7.2  |
| Aragorn 	|  192.168.0.20	|  16 GB | 12 vCPU 	|  250 GB	|  AMD Ryzen 5 2600X	|  Proxmox 7.2	|
| Legolas	|  192.168.0.30	|  4 GB	 |  4 vCPU  |  250 GB	|  i5-3337U 	        |  Ubuntu 22.04	|

___

## Tech stack

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img width="32" src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg"></td>
        <td><a href="https://kubernetes.io/">Kubernetes</a></td>
        <td>Maian Character of this project</td>
    </tr>
     <tr>
        <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/0/04/Terraform_Logo.svg"></td>
        <td><a href="https://www.terraform.io/">Terraform</a></td>
        <td>IaC tool for local VM and cloud resource provisioning</td>
    </tr>
    <tr>
        <td><img width="32" src="https://simpleicons.org/icons/ansible.svg"></td>
        <td><a href="https://www.ansible.com">Ansible</a></td>
        <td>Automate bare metal provisioning and configuration</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/argo/icon/color/argo-icon-color.svg"></td>
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
        <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/7/77/Rocky_Linux_logo.svg"></td>
        <td><a href="https://rockylinux.org/">Rocky Linux</a></td>
        <td>Base OS for Kubernetes nodes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg"></td>
        <td><a href="">Github</a></td>
        <td>Git service</td>
    </tr>
    <tr>
        <td><img width="32" src="https://grafana.com/static/img/menu/grafana2.svg"></td>
        <td><a href="https://grafana.com">Grafana</a></td>
        <td>Operational dashboards</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/helm/icon/color/helm-icon-color.svg"></td>
        <td><a href="https://helm.sh">Helm</a></td>
        <td>The package manager for Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/k3s/icon/color/k3s-icon-color.svg"></td>
        <td><a href="https://k3s.io">K3s</a></td>
        <td>Lightweight distribution of Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/kubernetes/icon/color/kubernetes-icon-color.svg"></td>
        <td><a href="https://kubernetes.io">Kubernetes</a></td>
        <td>Container-orchestration system, the backbone of this project</td>
    </tr>
    <tr>
        <td><img width="32" src="https://github.com/grafana/loki/blob/main/docs/sources/logo.png?raw=true"></td>
        <td><a href="https://grafana.com/oss/loki">Loki</a></td>
        <td>Log aggregation system</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/longhorn/icon/color/longhorn-icon-color.svg"></td>
        <td><a href="https://longhorn.io">Longhorn</a></td>
        <td>Cloud native distributed block storage for Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/60239468?s=200&v=4"></td>
        <td><a href="https://metallb.org">MetalLB</a></td>
        <td>Bare metal load-balancer for Kubernetes</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/1412239?s=200&v=4"></td>
        <td><a href="https://www.nginx.com">NGINX</a></td>
        <td>Kubernetes Ingress Controller</td>
    </tr>
    <tr>
        <td><img width="32" src="https://cncf-branding.netlify.app/img/projects/prometheus/icon/color/prometheus-icon-color.svg"></td>
        <td><a href="https://prometheus.io">Prometheus</a></td>
        <td>Systems monitoring and alerting toolkit</td>
    </tr>
    <tr>
        <td><img width="32" src="https://docs.renovatebot.com/assets/images/logo.png"></td>
        <td><a href="https://www.whitesourcesoftware.com/free-developer-tools/renovate">Renovate</a></td>
        <td>Automatically update dependencies</td>
    </tr>
    <tr>
        <td><img width="32" src="https://avatars.githubusercontent.com/u/47602533?s=200&v=4"></td>
        <td><a href="https://tekton.dev">Tekton</a></td>
        <td>Cloud native solution for building CI/CD systems</td>
    </tr>
    <tr>
        <td><img width="32" src="https://trow.io/trow.png"></td>
        <td><a href="https://trow.io">Trow</a></td>
        <td>Private container registry</td>
    </tr>
    <tr>
        <td><img width="32" src="https://simpleicons.org/icons/vault.svg"></td>
        <td><a href="https://www.vaultproject.io">Vault</a></td>
        <td>Secrets and encryption management system</td>
    </tr>

</table>

___

## Network Topology

You can create your drawing using [Excalidraw](https://excalidraw.com/)

![Excalidraw](img/Excalidraw.png)

## Links to stores 

- [RAM: Corsair Vengeance LPX DDR4 3200 MHz- Amazon](https://www.amazon.it/Corsair-Vengeance-Memorie-Desktop-Prestazioni/dp/B0143UM4TC/ref=sr_1_2?crid=1OANRA2Q2Y6NF&keywords=corsair+vengeance+16gb+ddr4&qid=1684180523&sprefix=corsair+ve%2Caps%2C813&sr=8-2)
- [CASE: Sharkoon TG5](https://it.sharkoon.com/product/TG5)
- [Mothrerboard - ASUS ROG STRIX B450-F GAMING ](https://www.amazon.it/B450-F-GAMING-Scheda-Supporto-Doppia/dp/B07F714FT7/ref=sr_1_1?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=VRAX2WCGXJKZ&keywords=ROG+strix+b450&qid=1684180721&sprefix=rog+strix+b450%2Caps%2C165&sr=8-1)
- [CPU - AMD Ryzen 5 2600X](https://www.amazon.it/AMD-2600-6-Core-Wraith-Cooler/dp/B07B428V2L/ref=sr_1_1?__mk_it_IT=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=2YDOS5S5JGTXK&keywords=amd%2Bryzen%2B5%2B2600x&qid=1684180752&sprefix=amd%2Bryzen%2B5%2B2600x%2Caps%2C145&sr=8-1&th=1)


