---
hide:
  - toc
---
# Hardware

The below lists the hardware and some specs of my homelab & network infrastructure

| Device                    | OS Disk Size | Data Disk Size       | CPU | Ram  | Operating System | Name | Purpose |
|---------------------------|-------|-------|----------------------|-----|------|------------------|------------------------------|
| Lenovo M700 tiny | 128 GB | N/A | i3-6400t | 8 GB | Ubuntu 20.04 LTS | k3s-01 | Cluster Master |
| Lenovo M700 tiny | 128 GB | 512 GB NVMe (via USB) | i3-6400t | 8 GB | Ubuntu 20.04 LTS | k3s-02 | Cluster Master |
| Lenovo M710 tiny | 128 GB | 512 GB NVMe | i5-6400t | 24 GB | Ubuntu 20.04 LTS | k3s-03 | Cluster Master |
| Lenovo M710 tiny | 128 GB | 512 GB NVMe | i5-6400t | 24 GB | Ubuntu 20.04 LTS | k3s-04 | Cluster Worker |
| Raspberry Pi 4 | 128 GB USB HDD | N/A | 4 GB | Ubuntu 20.04.LTS | k3s-rpi-01 | Cluster Worker |
| Raspberry Pi 4 | 128 GB USB HDD | N/A | 4 GB | Ubuntu 20.04.LTS | k3s-rpi-02 | Cluster Worker |
| Raspberry Pi 4 | 128 GB USB HDD | N/A | 4 GB | Ubuntu 20.04.LTS | k3s-rpi-03 | Cluster Worker |
