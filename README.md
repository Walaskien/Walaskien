# Stanislav Petnichenko

DevOps / infrastructure engineer. Linux, virtualization, networks, monitoring, Kubernetes on kubeadm. Based in Minsk, working remotely.

## What I build

| Project | What it does |
|---|---|
| [queue-saturation-observability](https://github.com/Walaskien/queue-saturation-observability) | Prometheus, Alertmanager and Grafana stack with an exporter that tells a slow consumer from a busy host. Alerts are covered by `promtool` tests. |
| [ansible-linux-baseline](https://github.com/Walaskien/ansible-linux-baseline) | Ansible roles for a server baseline: users, SSH hardening, nftables, node_exporter. Tested in containers (Ubuntu, Debian, Rocky); the second run gives `changed=0`. |
| [mikrotik-site-to-site](https://github.com/Walaskien/mikrotik-site-to-site) | Generates RouterOS 7 configs for a WireGuard mesh with a backup link from one YAML file. |
| [single-node-k8s-platform](https://github.com/Walaskien/single-node-k8s-platform) | Single-node Kubernetes lab on k3d with private PKI, TLS ingress, PostgreSQL backups and Grafana; the kubeadm node is documented and scripted. CI brings it up and restores a backup. |
| [backup-restore-verification](https://github.com/Walaskien/backup-restore-verification) | Postgres backups that are restored into a throwaway container and checked, with the result in Prometheus. |
| [dual-homed-routing](https://github.com/Walaskien/dual-homed-routing) | Why replies leave through the wrong interface on a host with two uplinks, with a check script and a netplan example. |
| [apple-tls-398](https://github.com/Walaskien/apple-tls-398) | Apple clients rejecting long-lived internal TLS certificates: limits, a check script, a cert-manager example. |

## Stack

Linux · VMware / Proxmox · Veeam · Docker · Kubernetes (kubeadm, Helm, ingress, cert-manager) · Prometheus / Grafana / Zabbix · Ansible · Bash / Python · MikroTik · WireGuard / IPsec · GitHub Actions
