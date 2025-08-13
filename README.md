# Home DevOps Lab

This repository documents my personal home lab used for learning DevOps, cloud-native technologies, and system automation.
It acts as a central hub linking all my other related projects.

---

## Current Status

### Hardware:
- **Raspbery Pi5** running: 
    * MagicMirror smart display, 
    * Grafana Server, 
    * Prometheus, 
    * Node Exporter
- **2 * Raspberry Pi 4** - reseved for bare-metal Kubernetes cluster. Reserved for monitoring node.
- **1 * Raspberry Pi 4** - reseved for bare-metal Kubernetes cluster. Runs kind clusters for Kuberneter learning.
- **Raspberry Pi 3** - with a connected screen is used to access MagicMirror. Reserved for monitoring node. Node exporter, SNMP Exporter.
- **2 * Mikrotik router, 1 * Mikrotik Switch** - home network
- **Local PC *2** - workstations with Kubuntu


### Software in use:
- MagicMirror - smart display platform
- Docker - Container runtime used for application and service deployement
- kind - Local Kubernetes cluster for testing and learning
- Prometheus - Monitoring system for collectiong metrics
- Node Exporter - Metrics exporter 
- Grafana - Visualization and dashboard platform for monitoring data


### Planned Work:
- `architecture.md` to be filled in
- Deploy Kubernetes cluster on 3 * RPi4 using kubeadm
- Configure Prometheus + Grafana monitoring with RPi4, Mikrotiks (Node Exporter, SNMP Exporter)
- Automate provisioning with Ansible
- Build CI/CD pipeline with GitHub Acions (maybe local Gitlab)
- Use Terraform for Infrastructure-as-Code experiments
- Connect MagicMirror to Kubernetes monitoring data
- Configuring alerting system (Alertmanager + Telegram notifications)
- Configure centralized logging (Loki + Promtail or ELK stack)
- Set up Kubernetes Ingress Controller with SSL/TLS (NGINX Ingress, Cert-Manager)
- Implement secrets management (Sealed Secrets, HashiCorp Vault)
- Add backup strategy for Kubernetes cluster and monitoring data
- Document lab setup and disaster recovery procedures
- Test failover and distaster recovery procedures

## Realted Repositories:
- [magicmirror-portfolio] (https://github.com/tmaciocha/magicmirror-portfolio)
- [monitoring-portfolio] (https://github.com/tmaciocha/monitoring-portfolio)
- [linix-lab-setup] (https://github.com/tmaciocha/linux-lab-setup)
- [portfolio-website] (https://github.com/tmaciocha/portfolio-website)

## Architecture
Initial and target architecture diagrams will be added in `architecture.md`
