# home-ops

My home k8s cluster built with the help of k8s@home managed by Flux GitOps

## Nodes
|          Node          | RAM  |  Storage   |   Role   | Operating System
| ---------------------- |------| -----------| -------- | ---------------- |
| Raspberry Pi 4 Model B | 4GB  | 800GB SSD  |  Master  | Ubuntu 20.04 LTS |
| Raspberry Pi 4 Model B | 4GB  | 120GB SSD  |  Master  | Ubuntu 20.04 LTS |
| Raspberry Pi 4 Model B | 4GB  | 120GB SSD  |  Master  | Ubuntu 20.04 LTS |
| VM Node                | 8GB  | 1TB NVMe   |  Worker  | Ubuntu 20.04 LTS |
| VM Node                | 8GB  | 1TB NVMe   |  Worker  | Ubuntu 20.04 LTS |
| VM Node                | 8GB  | 1TB NVMe   |  Worker  | Ubuntu 20.04 LTS |
| TrueNAS VM             | 16GB | 4x4TB      |  NAS     | Ubuntu 20.04 LTS |


## Cluster

- Proxmox Host
- Traefik Ingress
- Rook Ceph
- TrueNAS

## Automations
- [Renovate](https://github.com/renovatebot/renovate)
