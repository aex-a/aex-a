![Header](header.png)

git ⌬ 1970-01-01T00:00:00Z  
↯ aex-a $ fastfetch

SYSTEM INFORMATION  
ROLE \- NOC Technician II \-\> Cloud Operations & Observability    
CERT \- RHCSA (ID: 250-187-358)  
OS \- openSUSE Tumbleweed \/ Fedora \/ RHEL 10  
IAC \- OpenTofu \/ Terraform \/ GCP   
AUTOMATION \- Ansible \/ Bash \/ GitHub Actions  
CONTAINERS \- Kubernetes (K3s) \/ Podman \/ Helm  
OBSERVABILITY \- Prometheus \/ Grafana \/ Dynatrace  
NETWORKING \- VPC \/ OpenWRT \/ firewall-cmd \/ wg  
SECURITY \- SELinux \/ PCI Compliance \/ Lynis  

## 🐧 feat/projects

### [k3s-observatory](https://github.com/aex-a/k3s-observatory) | `Kubernetes` `Prometheus` `Helm` `GCP`
Bootstrapped an ephemeral, single-node K3s cluster on GCP via OpenTofu. Deployed the `kube-prometheus-stack` via Helm to execute synthetic Blackbox probes, featuring comprehensive Architecture Decision Records (ADRs) to document MVP technical debt and zero-trust port-forwarding constraints.

### [ot-trek](https://github.com/aex-a/ot-trek) | `OpenTofu` `GCP` `IaC`
Architected a modular, scalable Google Cloud Platform environment entirely via Infrastructure as Code. 
Features strict SSH firewall rules and zero-touch deployment pipelines utilizing `metadata_startup_scripts`
for automated dependency injection.

### [tux-utils](https://github.com/aex-a/tux-utils) | `Bash` `Systemd` `Linux`
A suite of robust Bash utilities engineered for Linux environments.
**q-length.sh**: A dual-mode network socket/queue monitoring tool integrated directly as a native `systemd`
daemon with signal trapping (SIGINT/SIGTERM) for graceful shutdowns.
