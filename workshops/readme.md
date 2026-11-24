# AWS Networking Workshops

Hands-on workshops for the networking session. Each workshop runs in an AWS-provided sandbox account (for example through an AWS Activation Day or a team-led event) or in your own account using the linked infrastructure-as-code.

> Workshop resources incur costs in your own account. Delete them when you finish.

## Workshops by service

| Service | Workshop | Source code |
|---|---|---|
| AWS Cloud WAN | [AWS Cloud WAN Workshop](https://catalog.workshops.aws/cloudwan/en-US) | [aws-cloudwan-workshop-code](https://github.com/aws-samples/aws-cloudwan-workshop-code) (CloudFormation and Terraform) |
| AWS Cloud WAN, Network Firewall, Route 53 DNS Firewall | [Building Secure Networks with AWS Cloud WAN, Network Firewall, and DNS Firewall](https://catalog.us-east-1.prod.workshops.aws/workshops/cdef9a06-8156-4669-9e6a-6eb83e4a5adc/en-US) | [sample-building-secure-global-hybrid-networks-on-aws-workshop](https://github.com/aws-samples/sample-building-secure-global-hybrid-networks-on-aws-workshop) |
| AWS Network Firewall, Route 53 DNS Firewall, AWS Transit Gateway | [AWS Advanced Network Security: Network Firewall and DNS Firewall](https://catalog.workshops.aws/network-security/en-US) | [sample-aws-network-security-workshop](https://github.com/aws-samples/sample-aws-network-security-workshop) |

## Coverage by service

### AWS Cloud WAN
- [AWS Cloud WAN Workshop](https://catalog.workshops.aws/cloudwan/en-US): build a global network with core network policies, segments, and attachments.
- [Building Secure Networks with AWS Cloud WAN, Network Firewall, and DNS Firewall](https://catalog.us-east-1.prod.workshops.aws/workshops/cdef9a06-8156-4669-9e6a-6eb83e4a5adc/en-US): Cloud WAN as the central hub, including service insertion to route traffic through a firewall.

### Amazon Route 53 Resolver DNS Firewall
- [AWS Advanced Network Security](https://catalog.workshops.aws/network-security/en-US): domain filtering, managed rules, and logging.
- [Building Secure Networks with AWS Cloud WAN, Network Firewall, and DNS Firewall](https://catalog.us-east-1.prod.workshops.aws/workshops/cdef9a06-8156-4669-9e6a-6eb83e4a5adc/en-US): the same DNS Firewall content with a Cloud WAN hub.
- Docs: [Getting started with Resolver DNS Firewall](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resolver-dns-firewall-getting-started.html)

### AWS Network Firewall
- [AWS Advanced Network Security](https://catalog.workshops.aws/network-security/en-US): centralized deployment with Transit Gateway and Suricata rule writing.
- [Building Secure Networks with AWS Cloud WAN, Network Firewall, and DNS Firewall](https://catalog.us-east-1.prod.workshops.aws/workshops/cdef9a06-8156-4669-9e6a-6eb83e4a5adc/en-US): centralized inspection with Cloud WAN.
- Docs: [Getting started with AWS Network Firewall](https://docs.aws.amazon.com/network-firewall/latest/developerguide/getting-started.html)

### AWS Transit Gateway
- [AWS Advanced Network Security](https://catalog.workshops.aws/network-security/en-US): uses Transit Gateway as the centralized networking hub for firewall inspection.
- Docs: [Tutorial: Create a transit gateway using the Amazon VPC console](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-getting-started-console.html)
- Docs: [Tutorial: Create a transit gateway using the AWS CLI](https://docs.aws.amazon.com/vpc/latest/tgw/tgw-getting-started-cli.html)

## More

- Browse all workshops: [AWS Workshop Studio catalog](https://catalog.workshops.aws)
- Reference list: [AWS Network Firewall additional references](https://aws.github.io/aws-security-services-best-practices/guides/network-firewall/additional-references/docs/)
