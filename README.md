# Marco Medde

DevOps and platform engineer in Switzerland. I build infrastructure where the whole system is code: NixOS flakes for every host, Terraform for every cloud account, and pipelines that ship complete, tested systems instead of scripts.

**What I work on**

- NixOS fleets on AWS Graviton and Hetzner: built and VM-tested in CI, served from an Attic binary cache, deployed pull-based with automatic rollback
- AWS Organizations in Terraform, SSO-only access, secrets in SOPS with KMS
- Prometheus, Grafana and Alertmanager over a Tailscale mesh
- AI-assisted engineering: coding agents are part of my daily loop

**Selected work**

- [nixos-fleet-pipeline](https://github.com/marcothedood/nixos-fleet-pipeline): CI builds the exact system each node runs; nodes pull, switch and roll back on their own
- [wpbox](https://github.com/marcothedood/wpbox): architecture of the NixOS platform behind ~45 production WordPress sites
- [nixos-anywhere](https://github.com/Martel-IT/nixos-anywhere): NixOS bootstrap with disko for x86 and Graviton nodes
- [eros4nrg](https://github.com/marcothedood/eros4nrg): Kubernetes data platform for the NEMO Horizon Europe project (Kustomize, Flux, EKS)
- [odoo16-nixos](https://github.com/marcothedood/odoo16-nixos): Odoo on NixOS from a single flake

Most of my work lives in private repositories; the contribution graph counts it.

[LinkedIn](https://linkedin.com/in/marco-medde)
