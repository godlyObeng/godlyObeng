# Godly Obeng Karikari

Platform and Infrastructure Engineer, based in Greater Manchester.

I build and own Kubernetes platforms: cluster lifecycle, highly available service exposure, GitOps delivery, identity, storage and the on-call work that comes with running something people depend on. Most of my time goes on building platforms that are documented well enough for another engineer to support without me.

Currently working on Kubernetes and security platforms in a distributed UK and US team, and open to platform or infrastructure engineering roles.

## What I work with

| Area | Tools |
| --- | --- |
| Platforms | Kubernetes, RKE2, kubeadm, Helm, Rancher, Proxmox |
| Cloud and IaC | AWS EKS and EC2, Terraform, Pulumi, Ansible, Packer |
| Delivery | GitLab CI/CD, GitOps with Rancher Fleet and Argo CD |
| Networking | Cilium, ClusterMesh, kube-vip, MetalLB, BGP, network policy |
| Data and identity | CloudNativePG, Longhorn, MinIO, Keycloak and OpenID Connect |
| Reliability | On-call incident response, Prometheus, Grafana, OpenSearch, Graylog |
| Languages | Python, Bash, C and Pro*C, PL/SQL |

## Homelab

I run a multi-node Kubernetes platform at home: RKE2 on Flatcar Linux across a Proxmox cluster, provisioned with Pulumi, using Cilium for the datapath and load balancing, kube-vip for the API endpoint, Longhorn and CloudNativePG for state, Rancher Fleet for delivery and Keycloak for single sign-on.

The architecture and the reasoning behind each decision are documented here:

**[github.com/godlyObeng/homelab-k8s](https://github.com/godlyObeng/homelab-k8s)**

## Writing

I write up the things that took me a while to get right. Recent example:

**[Give your bare-metal cluster real LoadBalancer IPs with Cilium](https://blog.godlyobeng.com/cilium-loadbalancer-l2-service/)**

More at [blog.godlyobeng.com](https://blog.godlyobeng.com).

## Contact

me@godlyobeng.com

<!---
godlyObeng/godlyObeng is a special repository because its README.md appears on my GitHub profile.
--->
