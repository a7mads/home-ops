# home-cluster

My home k8s cluster built with the help of k8s@home managed by Flux GitOps

## 💻 Nodes
|          Node          | RAM  |  Storage   |     Role       | Operating System
| ---------------------- |------| -----------| -------------- | ---------------- |
| Raspberry Pi 4 Model B | 4GB  | 800GB SSD  |  Master Node   | Ubuntu 20.04 LTS |
| Raspberry Pi 4 Model B | 4GB  | 120GB SSD  |  Master Node   | Ubuntu 20.04 LTS |
| Raspberry Pi 4 Model B | 4GB  | 120GB SSD  |  Master Node   | Ubuntu 20.04 LTS |
| VM Node                | 8GB  | 1TB NVMe   |  Worker Node   | Ubuntu 20.04 LTS |
| VM Node                | 8GB  | 1TB NVMe   |  Worker Node   | Ubuntu 20.04 LTS |
| VM Node                | 8GB  | 1TB NVMe   |  Worker Node   | Ubuntu 20.04 LTS |

## Cluster

- Proxmox PVE Host
- Traefik Ingress
- Rook Ceph
- TrueNAS 8x Tib

## Automations
- [Renovate](https://github.com/renovatebot/renovate)
- [Renovate Helm Releases](https://github.com/k8s-at-home/renovate-helm-releases)
