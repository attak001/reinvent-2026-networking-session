# re:Invent 2026 Networking Session: Documentation

Reference links for the AWS networking services covered in this session. Each section lists the official documentation, best practices, and useful additional resources.

## Contents

- [AWS Transit Gateway](#aws-transit-gateway)
- [AWS Direct Connect](#aws-direct-connect)
- [AWS Cloud WAN](#aws-cloud-wan)
- [AWS Network Firewall](#aws-network-firewall)
- [Amazon Route 53 Resolver DNS Firewall](#amazon-route-53-resolver-dns-firewall)
- [Cross-service resources](#cross-service-resources)

---

## AWS Transit Gateway

### Documentation
- [Product page](https://aws.amazon.com/transit-gateway/)
- [What is a transit gateway?](https://docs.aws.amazon.com/vpc/latest/tgw/what-is-transit-gateway.html)
- [Transit Gateway user guide](https://docs.aws.amazon.com/vpc/latest/tgw/)
- [How transit gateways work](https://docs.aws.amazon.com/vpc/latest/tgw/how-transit-gateways-work.html)
- [Transit gateway route tables](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-route-tables.html)
- [Transit gateway peering attachments](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-peering.html)
- [Quotas for transit gateways](https://docs.aws.amazon.com/vpc/latest/tgw/transit-gateway-quotas.html)
- [Pricing](https://aws.amazon.com/transit-gateway/pricing/)
- [FAQs](https://aws.amazon.com/transit-gateway/faqs/)

### Best practices
- [Transit gateway design best practices](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-best-design-practices.html)
- [Building a scalable and secure multi-VPC AWS network infrastructure (whitepaper)](https://docs.aws.amazon.com/whitepapers/latest/building-scalable-secure-multi-vpc-network-infrastructure/welcome.html)
- [Transit gateway centralized router scenario](https://docs.aws.amazon.com/vpc/latest/tgw/transit-gateway-isolated.html)
- [Centralized inspection architecture with Transit Gateway](https://docs.aws.amazon.com/vpc/latest/tgw/transit-gateway-appliance-scenario.html)

### Useful links
- [Monitoring with CloudWatch](https://docs.aws.amazon.com/vpc/latest/tgw/transit-gateway-cloudwatch-metrics.html)
- [Transit Gateway Flow Logs](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-flow-logs.html)
- [Network Manager (global view of Transit Gateway networks)](https://docs.aws.amazon.com/network-manager/latest/tgwnm/what-are-tgnm.html)
- [Transit Gateway Connect (SD-WAN)](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-connect.html)
- [Transit Gateway Multicast](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-multicast-overview.html)

---

## AWS Direct Connect

### Documentation
- [Product page](https://aws.amazon.com/directconnect/)
- [What is AWS Direct Connect?](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html)
- [Direct Connect user guide](https://docs.aws.amazon.com/directconnect/latest/UserGuide/)
- [Direct Connect connections](https://docs.aws.amazon.com/directconnect/latest/UserGuide/WorkingWithConnections.html)
- [Virtual interfaces](https://docs.aws.amazon.com/directconnect/latest/UserGuide/WorkingWithVirtualInterfaces.html)
- [Direct Connect gateways](https://docs.aws.amazon.com/directconnect/latest/UserGuide/direct-connect-gateways.html)
- [Direct Connect locations](https://aws.amazon.com/directconnect/locations/)
- [Pricing](https://aws.amazon.com/directconnect/pricing/)
- [FAQs](https://aws.amazon.com/directconnect/faqs/)

### Best practices
- [Resiliency recommendations](https://aws.amazon.com/directconnect/resiliency-recommendation/)
- [Direct Connect Resiliency Toolkit](https://docs.aws.amazon.com/directconnect/latest/UserGuide/resilency_toolkit.html)
- [Security in AWS Direct Connect (MACsec and more)](https://docs.aws.amazon.com/directconnect/latest/UserGuide/security.html)
- [MAC security](https://docs.aws.amazon.com/directconnect/latest/UserGuide/MACsec.html)
- [Hybrid connectivity whitepaper](https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/introduction.html)
- [Amazon VPC connectivity options whitepaper](https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/welcome.html)

### Useful links
- [Routing policies and BGP communities](https://docs.aws.amazon.com/directconnect/latest/UserGuide/routing-and-bgp.html)
- [Monitoring Direct Connect](https://docs.aws.amazon.com/directconnect/latest/UserGuide/monitoring-overview.html)
- [Troubleshooting Direct Connect](https://docs.aws.amazon.com/directconnect/latest/UserGuide/troubleshooting-dx.html)
- [Direct Connect SiteLink](https://docs.aws.amazon.com/directconnect/latest/UserGuide/sitelink.html)
- [Direct Connect quotas](https://docs.aws.amazon.com/directconnect/latest/UserGuide/limits.html)

---

## AWS Cloud WAN

### Documentation
- [Product page](https://aws.amazon.com/cloud-wan/)
- [What is AWS Cloud WAN?](https://docs.aws.amazon.com/network-manager/latest/cloudwan/what-is-cloudwan.html)
- [Cloud WAN user guide](https://docs.aws.amazon.com/network-manager/latest/cloudwan/)
- [Cloud WAN core network policy](https://docs.aws.amazon.com/network-manager/latest/cloudwan/cloudwan-policy-change-sets.html)
- [Core network policy parameters](https://docs.aws.amazon.com/network-manager/latest/cloudwan/cloudwan-policies-json.html)
- [Cloud WAN attachments](https://docs.aws.amazon.com/network-manager/latest/cloudwan/cloudwan-attachments.html)
- [Cloud WAN segments](https://docs.aws.amazon.com/network-manager/latest/cloudwan/cloudwan-segments-networks.html)
- [Quotas](https://docs.aws.amazon.com/network-manager/latest/cloudwan/cloudwan-quotas.html)
- [Pricing](https://aws.amazon.com/cloud-wan/pricing/)
- [FAQs](https://aws.amazon.com/cloud-wan/faqs/)

### Best practices
- [Building a global network using AWS Cloud WAN (whitepaper)](https://docs.aws.amazon.com/whitepapers/latest/building-scalable-secure-multi-vpc-network-infrastructure/aws-cloud-wan.html)
- [Service insertion and network function groups](https://docs.aws.amazon.com/network-manager/latest/cloudwan/cloudwan-service-insertion.html)

### Useful links
- [Cloud WAN events and monitoring](https://docs.aws.amazon.com/network-manager/latest/cloudwan/cloudwan-monitoring.html)
- [Network Manager console and global dashboard](https://docs.aws.amazon.com/network-manager/latest/cloudwan/cloudwan-network-manager.html)
- [AWS::NetworkManager::CoreNetwork (CloudFormation)](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-networkmanager-corenetwork.html)

---

## AWS Network Firewall

AWS Network Firewall is a managed, stateful network firewall and intrusion detection and prevention service for Amazon VPC. It filters traffic at the VPC perimeter and between subnets, VPCs, and networks. AWS provisions and scales the firewall endpoints for you, and you define the rules. Rules can be simple 5-tuple and domain filters, or Suricata-compatible IPS rules.

### Key features

| Feature | What it does | Documentation |
| --- | --- | --- |
| Firewall | The resource that you deploy into VPC subnets through firewall endpoints. It is tied to one firewall policy. | [Firewalls](https://docs.aws.amazon.com/network-firewall/latest/developerguide/firewalls.html) |
| Firewall policy | Defines the behavior of a firewall: which rule groups to use and the default actions for traffic that matches no rule. | [Firewall policies](https://docs.aws.amazon.com/network-firewall/latest/developerguide/firewall-policies.html) |
| Rule groups | Reusable collections of rules, either stateless or stateful. | [Rule groups](https://docs.aws.amazon.com/network-firewall/latest/developerguide/rule-groups.html) |
| Stateless rules | Inspect each packet in isolation, using 5-tuple matching. | [Stateless rule groups](https://docs.aws.amazon.com/network-firewall/latest/developerguide/stateless-rule-groups-standard.html) |
| Stateful rules | Inspect traffic in the context of flows. They support 5-tuple, domain list, and Suricata-compatible rules. | [Stateful rule groups](https://docs.aws.amazon.com/network-firewall/latest/developerguide/stateful-rule-groups-suricata.html) |
| Domain filtering | Allow or deny HTTP and HTTPS traffic by domain name. | [Domain list rule groups](https://docs.aws.amazon.com/network-firewall/latest/developerguide/stateful-rule-groups-domain-names.html) |
| IPS rules | Intrusion prevention with Suricata-compatible rule strings. | [Suricata rule groups](https://docs.aws.amazon.com/network-firewall/latest/developerguide/stateful-rule-groups-suricata.html), [Suricata examples](https://docs.aws.amazon.com/network-firewall/latest/developerguide/suricata-examples.html) |
| IP set rules | Match on source and destination IP addresses. | [IP set rule groups](https://docs.aws.amazon.com/network-firewall/latest/developerguide/stateful-rule-groups-ips.html) |
| Rule evaluation order | Controls how stateful rules are processed (strict order or action order). | [Evaluation order](https://docs.aws.amazon.com/network-firewall/latest/developerguide/suricata-rule-evaluation-order.html) |
| TLS inspection | Decrypts, inspects, and re-encrypts TLS traffic. | [TLS inspection configurations](https://docs.aws.amazon.com/network-firewall/latest/developerguide/tls-inspection-configurations.html) |
| Transit Gateway integration | Attach a firewall directly to a transit gateway for centralized inspection. | [Transit gateway-attached firewalls](https://docs.aws.amazon.com/network-firewall/latest/developerguide/tgw-firewall.html) |
| Logging and monitoring | Alert and flow logs to Amazon S3, CloudWatch Logs, or Amazon Data Firehose. | [Logging and monitoring](https://docs.aws.amazon.com/network-firewall/latest/developerguide/logging-monitoring.html) |

### Documentation
- [Product page](https://aws.amazon.com/network-firewall/)
- [What is AWS Network Firewall?](https://docs.aws.amazon.com/network-firewall/latest/developerguide/what-is-aws-network-firewall.html)
- [Network Firewall developer guide](https://docs.aws.amazon.com/network-firewall/latest/developerguide/)
- [Components and how they fit together](https://docs.aws.amazon.com/network-firewall/latest/developerguide/firewall-components.html)
- [Rule groups](https://docs.aws.amazon.com/network-firewall/latest/developerguide/rule-groups.html)
- [Firewall policies](https://docs.aws.amazon.com/network-firewall/latest/developerguide/firewall-policies.html)
- [TLS inspection](https://docs.aws.amazon.com/network-firewall/latest/developerguide/tls-inspection.html)
- [Transit gateway-attached firewalls](https://docs.aws.amazon.com/network-firewall/latest/developerguide/tgw-firewall.html)
- [Pricing](https://aws.amazon.com/network-firewall/pricing/)
- [FAQs](https://aws.amazon.com/network-firewall/faqs/)

### Best practices
- [Deployment architectures and use cases](https://docs.aws.amazon.com/network-firewall/latest/developerguide/architectures.html)
- [Rule evaluation order](https://docs.aws.amazon.com/network-firewall/latest/developerguide/suricata-rule-evaluation-order.html)
- [Deployment models for AWS Network Firewall (blog)](https://aws.amazon.com/blogs/networking-and-content-delivery/deployment-models-for-aws-network-firewall/)
- [Security in AWS Network Firewall](https://docs.aws.amazon.com/network-firewall/latest/developerguide/security.html)

### Useful links
- [Logging and monitoring](https://docs.aws.amazon.com/network-firewall/latest/developerguide/logging-monitoring.html)
- [Suricata rule examples](https://docs.aws.amazon.com/network-firewall/latest/developerguide/suricata-examples.html)
- [Suricata documentation](https://docs.suricata.io/)
- [AWS managed rule groups](https://docs.aws.amazon.com/network-firewall/latest/developerguide/aws-managed-rule-groups.html)
- [Quotas](https://docs.aws.amazon.com/network-firewall/latest/developerguide/quotas.html)
- [AWS Networking & Content Delivery blog](https://aws.amazon.com/blogs/networking-and-content-delivery/)

---

## Amazon Route 53 Resolver DNS Firewall

### Documentation
- [Product page (Route 53 Resolver DNS Firewall)](https://aws.amazon.com/route53/resolver-dns-firewall/)
- [Route 53 Resolver DNS Firewall](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-dns-firewall.html)
- [How DNS Firewall works](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-dns-firewall-overview.html)
- [Rule groups and rules](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-dns-firewall-rule-groups.html)
- [Domain lists](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-dns-firewall-domain-lists.html)
- [AWS managed domain lists](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-dns-firewall-managed-domain-lists.html)
- [Route 53 Resolver](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver.html)
- [Pricing](https://aws.amazon.com/route53/pricing/)
- [Route 53 FAQs](https://aws.amazon.com/route53/faqs/)

### Best practices
- [Route 53 Resolver DNS Firewall best practices](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/best-practices-resolver-dns-firewall.html)
- [Resolver DNS Firewall advanced protections (DNS tunneling and DGA)](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/firewall-advanced-protections.html)
- [Managing rule groups across accounts with AWS Firewall Manager](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-dns-firewall-managing-rule-groups.html)
- [Hybrid cloud DNS options for Amazon VPC (whitepaper)](https://docs.aws.amazon.com/whitepapers/latest/hybrid-cloud-dns-options-for-vpc/hybrid-cloud-dns-options-for-vpc.html)

### Useful links
- [DNS Firewall logging](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-query-logs.html)
- [Resolver query logging](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-query-logging.html)
- [DNS Firewall quotas](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/DNSLimitations.html#limits-api-entities-resolver-dns-firewall)

---

## Cross-service resources

- [AWS Networking & Content Delivery blog](https://aws.amazon.com/blogs/networking-and-content-delivery/)
- [AWS Well-Architected Framework: Reliability pillar, networking](https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/foundations.html)
- [AWS Security Reference Architecture: Network account](https://docs.aws.amazon.com/prescriptive-guidance/latest/security-reference-architecture/network.html)
- [Amazon VPC connectivity options (whitepaper)](https://docs.aws.amazon.com/whitepapers/latest/aws-vpc-connectivity-options/welcome.html)
- [AWS Reachability Analyzer](https://docs.aws.amazon.com/vpc/latest/reachability/what-is-reachability-analyzer.html)
- [AWS Firewall Manager](https://docs.aws.amazon.com/waf/latest/developerguide/fms-chapter.html)

> Links point to AWS documentation and may move over time. If one returns a 404, search the service's documentation index.
