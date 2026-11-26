# AWS Network Firewall

AWS Network Firewall is a managed, stateful network firewall and intrusion detection and prevention service for Amazon VPC. It filters traffic at the VPC perimeter and between subnets, VPCs, and networks. AWS provisions and scales the firewall endpoints for you, and you define the rules. Rules can be simple 5-tuple and domain filters, or Suricata-compatible IPS rules.

## Key features

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

## Getting started

- [What is AWS Network Firewall?](https://docs.aws.amazon.com/network-firewall/latest/developerguide/what-is-aws-network-firewall.html)
- [Components and how they fit together](https://docs.aws.amazon.com/network-firewall/latest/developerguide/firewall-components.html)
- [Deployment architectures and use cases](https://docs.aws.amazon.com/network-firewall/latest/developerguide/architectures.html)
- [Developer guide (full index)](https://docs.aws.amazon.com/network-firewall/latest/developerguide/)
