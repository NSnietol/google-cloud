# Network

## VPC

A Virtual Private Cloud (VPC) network is a virtual version of a physical network, implemented inside Google's production network. VPC networks are global resources, meaning that subnets can be created in any region without global VPC peering.

Is made up of subnets, routes, and firewall rules.

### Services associated

- Clould load balancer can be used to distribute traffic across multiple regions.
- Cloud CDN can be used to cache content close to users.
- Cloud interconnect can be used to connect to on-premises networks.
- Cloud DNS can be used to resolve domain names.

### VPC Sharing

- VPC Network Peering: Connects two VPC networks to each other.
- Shared VPC: Allows an organization to connect resources from multiple projects to a common VPC network.



### Load Balancing

Distributes incoming network traffic across multiple instances.

- Regional external
- HTTPs
- SSL Proxy
- TCP Proxy
- Internal