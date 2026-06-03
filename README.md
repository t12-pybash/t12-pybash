## Ciarán Donegan — Lead SRE

Infrastructure engineer with 14 years across fintech, blockchain, and enterprise cloud — Kubernetes, multi-cloud IaC, eBPF networking, and AI inference infrastructure. AWS Certified Solutions Architect.

---

### What I build

**[homelab-gitops](https://github.com/t12-pybash/homelab-gitops)** — 5-node bare-metal Kubernetes cluster with Cilium eBPF networking, Flux GitOps, and a fully airgapped private AI platform: Ollama GPU inference, LiteLLM, Open-WebUI, Qdrant RAG pipeline. Falco runtime detection, SOPS-encrypted secrets, default-deny NetworkPolicies, Velero backups.

**[sre-cli](https://github.com/t12-pybash/sre-cli)** — Custom SRE CLI and MCP server: live Prometheus/Alertmanager queries, semantic runbook search over a local knowledge base (Qdrant + Ollama embeddings), incident lifecycle management. Runs entirely on-cluster — no data leaves the environment.

**[fullnode-infrastructure](https://github.com/t12-pybash/fullnode-infrastructure)** — Production-grade OP Stack (Ethereum L1/L2) node infrastructure on AWS EKS. Kubernetes StatefulSets, Terraform, Cilium network policies, custom Prometheus blockchain metrics exporter.

---

### Stack

```
Cloud         AWS (CSA) · Azure · GCP · OCI · Bare metal (OVH, Equinix, Hetzner)
Kubernetes    kubeadm · EKS · Talos · Flux CD · ArgoCD · Helm · Kustomize
Networking    Cilium · eBPF · Hubble · Calico · WireGuard · pfSense · F5
IaC           Terraform · Terragrunt · Ansible · Bicep
Security      Falco · FedRAMP · SOC 2 · PCI DSS · SOPS · NetworkPolicies
Observability Prometheus · Grafana · Loki · Alertmanager · custom exporters
AI Infra      Ollama · LiteLLM · Qdrant · Redpanda · RAG pipelines · GPU scheduling
Languages     Python · Go · Bash
```

---

**[t-12.io](https://t-12.io)** · **[LinkedIn](https://www.linkedin.com/in/cdonegan7/)** · Cork, Ireland
