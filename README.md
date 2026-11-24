# Stanislav Petnichenko

DevOps / infrastructure engineer. Linux, virtualization, networks, monitoring, Kubernetes on kubeadm. Based in Minsk, working remotely.

## Projects

- [single-node-k8s-platform](https://github.com/Walaskien/single-node-k8s-platform): single-node Kubernetes lab on k3d with private PKI, TLS ingress, PostgreSQL backups and Grafana. The kubeadm node is documented and scripted.
- [cicd-k8s-delivery](https://github.com/Walaskien/cicd-k8s-delivery): Flask app delivered to a kind cluster by GitHub Actions, with Helm deploy, smoke test and rollback.
- [gitops-argocd](https://github.com/Walaskien/gitops-argocd): Argo CD app-of-apps for two environments with Kustomize overlays and an end-to-end job on kind.
- [vault-k8s-secrets](https://github.com/Walaskien/vault-k8s-secrets): Vault in dev mode and External Secrets Operator feeding a Kubernetes Secret. A demo lab, not a hardened setup.
- [sre-slo-observability](https://github.com/Walaskien/sre-slo-observability): SLOs and burn-rate alerts for a small HTTP service on Docker Compose with Prometheus, Alertmanager, Grafana and Loki.
- [queue-saturation-observability](https://github.com/Walaskien/queue-saturation-observability): Prometheus stack with an exporter that tells a slow consumer from a busy host. Alerts are covered by `promtool` tests.
- [ansible-linux-baseline](https://github.com/Walaskien/ansible-linux-baseline): Ansible roles for a server baseline (users, SSH, nftables, node_exporter), tested in containers on Ubuntu, Debian and Rocky.
- [backup-restore-verification](https://github.com/Walaskien/backup-restore-verification): Postgres backups restored into a throwaway container and checked, with the result in Prometheus.
- [mikrotik-site-to-site](https://github.com/Walaskien/mikrotik-site-to-site): generates RouterOS 7 configs for a WireGuard mesh with a backup link from one YAML file.
- [dual-homed-routing](https://github.com/Walaskien/dual-homed-routing): why replies leave through the wrong interface on a host with two uplinks, with a check script.
- [apple-tls-398](https://github.com/Walaskien/apple-tls-398): Apple clients rejecting long-lived internal TLS certificates, with a check script and a cert-manager example.

## Stack

Linux · VMware / Proxmox · Veeam · Docker · Kubernetes (kubeadm, Helm, ingress, cert-manager) · Prometheus / Grafana / Zabbix · Ansible · Bash / Python · MikroTik · WireGuard / IPsec · GitHub Actions
