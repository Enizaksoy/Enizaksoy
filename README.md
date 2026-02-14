# Hi, I'm Eniz Aksoy

**CCIE #23970 | Senior Network Architect | AI/ML Infrastructure**

Building AI GPU clusters and data center networks — from bare metal to distributed training.

---

### What I Do

- Design and build **RDMA-capable AI training clusters** with lossless Ethernet (RoCEv2, PFC/ECN)
- Architect **Spine-Leaf data center fabrics** with BGP EVPN VXLAN
- Integrate **multi-vendor networks** (Cisco, NVIDIA Cumulus, Versa SD-WAN)
- Monitor everything with **Prometheus + Grafana** dashboards
- Automate with **Python, Ansible, and Claude Code**

---

### Featured Projects

#### AI/GPU Cluster Lab
> 2-Spine / 2-Leaf Clos fabric with Cisco Nexus 9332PQ, RDMA rail design, QoS/PFC/ECN for lossless RoCEv2

| Metric | Result |
|--------|--------|
| RDMA Bandwidth (same-rail) | **38.98 Gb/s** (line-rate 40GbE) |
| RDMA Bandwidth (cross-rail) | **38.94 Gb/s** |
| RDMA Latency (same-rail) | **~3 us** |
| RDMA Latency (cross-rail) | **~5.4 us** |

[View Live Documentation](https://enizaksoy.github.io/) | [Source](https://github.com/Enizaksoy/enizaksoy.github.io)

#### Multi-Vendor EVPN VXLAN Integration
> Cisco Catalyst 9300 + Versa FlexVNF + Cumulus Linux (NVIDIA) — iBGP EVPN with Route Reflector, VXLAN-GBP interop fix

[View Live Documentation](https://enizaksoy.github.io/Multi-Vendor-VXLAN-EVPN-TEST-Cisco-Versa-Cumulus/) | [Source](https://github.com/Enizaksoy/Multi-Vendor-VXLAN-EVPN-TEST-Cisco-Versa-Cumulus)

#### Lossless Ethernet Monitoring
> Prometheus + Grafana monitoring for RoCE/RDMA networks — 40M+ ECN packets, 133M+ pause frames tracked

[Source](https://github.com/Enizaksoy/lossless-ethernet-monitoring)

#### RoCEv2 ECN & CNP Deep Dive
> Real packet captures from RDMA AI cluster analyzing congestion control mechanisms

[Source](https://github.com/Enizaksoy/ROCEV2_ECN_CNP_DEEP_DIVE)

---

### Tech Stack

**Networking:** Cisco NX-OS, NVIDIA Cumulus, Versa SD-WAN, BGP, OSPF, EVPN/VXLAN, RDMA/RoCEv2, PFC/ECN, LISP

**AI Infrastructure:** NVIDIA V100, Mellanox ConnectX, NCCL, MPI, PyTorch DDP, SLURM

**Monitoring:** Grafana, Prometheus, SNMP, Streaming Telemetry

**Automation:** Python, Ansible, Netmiko, Paramiko, Claude Code

---

### Certifications

**CCIE #23970** — Cisco Certified Internetwork Expert

---

### All Repositories

| Repository | Description |
|------------|-------------|
| [lab-baremetal-gpu-cluster](https://github.com/Enizaksoy/lab-baremetal-gpu-cluster) | Bare metal AI training cluster with V100 GPUs and RDMA networking |
| [rdma-ai-cluster](https://github.com/Enizaksoy/rdma-ai-cluster) | Lossless RDMA network for distributed AI training — 96% packet drop reduction |
| [ROCEV2_ECN_CNP_DEEP_DIVE](https://github.com/Enizaksoy/ROCEV2_ECN_CNP_DEEP_DIVE) | Deep dive into RoCEv2 ECN & CNP with real packet captures |
| [lossless-ethernet-monitoring](https://github.com/Enizaksoy/lossless-ethernet-monitoring) | Prometheus + Grafana monitoring for lossless ethernet networks |
| [mpi-ai-cluster-benchmark](https://github.com/Enizaksoy/mpi-ai-cluster-benchmark) | MPI benchmark suite for RDMA AI clusters |
| [Multi-Vendor-VXLAN-EVPN-TEST](https://github.com/Enizaksoy/Multi-Vendor-VXLAN-EVPN-TEST-Cisco-Versa-Cumulus) | Cisco + Versa + Cumulus EVPN VXLAN integration |
| [cisco-multi-site-evpn](https://github.com/Enizaksoy/cisco-multi-site-evpn-implementation) | Cisco CML multi-site EVPN automation |
| [EVPN-CISCO-with-VERSA](https://github.com/Enizaksoy/EVPN-CISCO-with-VERSA) | EVPN integration between Cisco and Versa SD-WAN |
| [ipsec-between-cisco-and-versa](https://github.com/Enizaksoy/ipsec-between-cisco-and-versa) | IPSec tunnel between Cisco and Versa platforms |
| [Nvidia_DC_LAB_2](https://github.com/Enizaksoy/Nvidia_DC_LAB_2) | NVIDIA Cumulus Linux data center lab |
| [LISP-Mobility](https://github.com/Enizaksoy/LISP-Mobility) | Cisco LISP Mobility lab |

---

*Built with real hardware, real packets, real results.*

