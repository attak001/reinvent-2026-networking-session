# Building the Foundation for a Multi-Region Global Betting Platform

### Companion resources for the re:Invent 2026 networking session

> 📱 **Got here from the QR code?** Welcome! This repository collects the documentation, blog posts, workshops and code samples behind the session, so you can go further after the talk.

**Speakers**

| | |
|---|---|
| **Kenneth Attard** | Enterprise Architect, Betsson Group |
| **Dimitrios Papageorgiou** | Senior Specialist Solutions Architect, Betting & Gaming, AWS |

---

## 🎯 Purpose

Betsson Group runs many brands, holds licences in 22 jurisdictions and serves customers in LatAm, CEECA, the Nordics and Western Europe. Supporting that footprint required a global network that is **secure, scalable and quick to extend into new regions**.

The session covers Betsson's AWS networking journey:

1. **Before 2019**: ad-hoc connectivity with IPsec over the internet, VPC peering, a single region, static routing and no infrastructure as code
2. **Phase 1 (2021–2022)**: a hub-and-spoke **AWS Transit Gateway** network built with IaC and connected to the Betsson Backbone over **AWS Direct Connect**
3. **Migration to AWS Cloud WAN (2023)**: segmentation, full-mesh routing and centralized policy, migrated with zero downtime
4. **Phase 2 (2024)**: optimized hybrid connectivity
5. **Phase 3 (Q4 2024 onward)**: security and observability using **AWS Network Firewall** and **Amazon Route 53 Resolver DNS Firewall**, with egress and east/west inspection

This repository holds the reading list that goes with the session.

---

## 📂 Repository structure

```
reinvent-2026-networking-session/
├── awscloudwan/                  # AWS Cloud WAN resources
├── awstransitgateway/            # AWS Transit Gateway resources
├── awsdirectconnect/             # AWS Direct Connect resources
├── awsnetworkfirewall/           # AWS Network Firewall resources
├── awsroute53resolverfirewall/   # Route 53 Resolver DNS Firewall resources
├── blogs/                        # Curated AWS Networking blog posts (Cloud WAN, newest first)
├── workshops/                    # Hands-on AWS Workshop Studio labs
├── otherdocs/                    # Best-practice guides and other references
└── README.md                     # You are here
```

| Folder | What you'll find |
|---|---|
| [`awscloudwan`](./awscloudwan) | Core networks, segments, core network policy, service insertion and Network Function Groups |
| [`awstransitgateway`](./awstransitgateway) | Regional hub routing, attachments, route tables, inter-region peering |
| [`awsdirectconnect`](./awsdirectconnect) | Dedicated and hosted connections, VIF types, resiliency models |
| [`awsnetworkfirewall`](./awsnetworkfirewall) | Stateful and stateless inspection, Suricata rules, managed threat signatures, Active Threat Defense |
| [`awsroute53resolverfirewall`](./awsroute53resolverfirewall) | Domain allow and deny lists, DNS tunneling and DGA protection, managed domain lists |
| [`blogs`](./blogs) | A dated list of AWS Networking & Content Delivery Blog posts about AWS Cloud WAN, from the 2021 preview to today |
| [`workshops`](./workshops) | Self-paced labs you can run in your own AWS account |
| [`otherdocs`](./otherdocs) | Security best-practice guides and IaC examples |

---

## ⭐ Start here

### re:Invent sessions
- **NET331**: AWS Cloud WAN MCP Server: Transform network operations with GenAI ([slides](https://d1.awsstatic.com/onedam/marketing-channels/website/aws/en_US/events/approved/reinvent-2025/reinvent/2025/slides/net/NET331_AWS-Cloud-WAN-MCP-Server-Transform-network-operations-with-GenAI.pdf))
- **NET401**: Deep dive into advanced routing policy with AWS Cloud WAN ([slides](https://d1.awsstatic.com/onedam/marketing-channels/website/aws/en_US/events/approved/reinvent-2025/reinvent/2025/slides/net/NET401_Deep-dive-into-advanced-routing-policy-with-AWS-Cloud-WAN.pdf))

### The Betsson story
- 📝 [How Betsson Services Limited elevated AWS hybrid connectivity to new heights with AWS Cloud WAN](https://aws.amazon.com/blogs/networking-and-content-delivery/how-betsson-services-limited-elevated-aws-hybrid-connectivity-to-new-heights-with-aws-cloud-wan/)

### Security best practices
- [AWS network security fundamentals](https://aws.github.io/aws-security-services-best-practices/guides/firewall-overview/)
- [AWS Network Firewall best practices](https://aws.github.io/aws-security-services-best-practices/guides/network-firewall/)
- [Route 53 Resolver DNS Firewall best practices](https://aws.github.io/aws-security-services-best-practices/guides/dns-firewall/)

### Hands-on workshops
- 🧪 [AWS Cloud WAN Workshop](https://catalog.workshops.aws/workshops/f3617759-f996-4c09-a498-9f771c3d4958/en-US)
- 🧪 [Securing AWS network traffic: Network Firewall & DNS Firewall](https://catalog.us-east-1.prod.workshops.aws/workshops/cbfa9f18-1175-4916-b7e7-e33dbbca9f9d/en-US)
- 🧪 [Approaches to layered security for Amazon VPC](https://catalog.us-east-1.prod.workshops.aws/workshops/04e6e6c8-c19b-40f9-8cc7-945669ca86b4/en-US)
- 🧪 [AWS Direct Connect Resiliency Workshop](https://catalog.us-east-1.prod.workshops.aws/workshops/6bce0ae3-2ab1-4541-b014-2647b429b710/en-US)
- 🧪 [AWS Direct Connect + Hybrid DNS Workshop](https://catalog.us-east-1.prod.workshops.aws/workshops/5a1ba4bb-e16a-4e40-9fdb-6c1925e73a73/en-US)

### Infrastructure as code
- 💻 [AWS Cloud WAN IaC examples (aws-samples)](https://github.com/aws-samples/aws-cloudwan-workshop-code)

---

## 📬 Contact

| | |
|---|---|
| **Kenneth Attard** | kenneth.attard@betssongroup.com · LinkedIn: `kenneth-attard` |
| **Dimitrios Papageorgiou** | dpapageo@amazon.com · LinkedIn: `dimitriospapageorgiou` |

---

<sub>All links point to public AWS documentation, blogs, workshops and samples. This repository is a curated reading list and does not contain official AWS guidance. Check the AWS documentation for current service features and regional availability.</sub>
