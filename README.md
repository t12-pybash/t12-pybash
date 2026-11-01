## Lead SRE | AI Platform Infrastructure | Kubernetes · Flux GitOps · Terraform · Private LLMs

---

## What I build

**[olympus-gitops](https://t-12.io/solutions/multi-cluster-setup-guide/)**: 5-node bare-metal Kubernetes cluster with Cilium eBPF networking, Flux GitOps, and a fully airgapped private AI platform: Ollama GPU inference, LiteLLM, Open-WebUI, Qdrant RAG pipeline. Falco runtime detection, SOPS-encrypted secrets, default-deny NetworkPolicies, Velero backups.

**[argus](https://t-12.io/solutions/argus-sre-agent/)**: Autonomous SRE agent: detects failing Kubernetes pods, diagnoses root cause via LLM, generates a GitOps patch, opens a GitLab MR, and deploys through Flux with Slack approval. Runs entirely on-cluster. No data leaves the environment.

**[fullnode-infrastructure](https://github.com/t12-pybash/fullnode-infrastructure)**: Production-grade OP Stack (Ethereum L1/L2) node infrastructure on AWS EKS. Kubernetes StatefulSets, Terraform, Cilium network policies, custom Prometheus blockchain metrics exporter.

---
## Stack

**Cloud** — AWS · Azure · GCP · OCI · Bare metal  
**Kubernetes** — kubeadm · EKS · Talos · Flux CD · ArgoCD · Helm · Kustomize  
**Networking** — Cilium · eBPF · Hubble · WireGuard · pfSense · Calico · F5  
**IaC** — Terraform · Terragrunt · Ansible · Bicep  
**CI/CD** — GitLab CI/CD · GitHub Actions  
**Observability** — Prometheus · Grafana · Loki · Alertmanager · DCGM · custom exporters  
**Security** — Falco · FedRAMP · SOC 2 · PCI DSS · GDPR · SOPS+age · NetworkPolicies  
**AI Infra** — Ollama · vLLM · LiteLLM · Qdrant · Redpanda · RAG pipelines · GPU scheduling  
**Languages** — Python · Go · Bash  

---

**[t-12.io](https://t-12.io)** · **[LinkedIn](https://www.linkedin.com/in/cdonegan7/)** · Cork, Ireland
