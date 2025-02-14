# IP Schema

Event fields used to define metadata about IP addresses in a network. It follows the standard from the Destination and Source categories.

## Data Fields

| Standard Name | Type | Description | Sample Value |
|--------|---------|-------|-------|
| ip_address | ip | IP address of the endpoint where the log was created | 8.8.8.8 |
| dst_ip_addr | ip | destination IP in a network connection (IPv4) | 8.8.8.8 |
| src_ip_addr | ip | source IP in a network connection (IPV4) | 192.168.1.2 |
| initiated | boolean | session | Flag to state the session was initiated or received | True |
| network_protocol | string | IP Protocol type for the connection (TCP/UDP/ICMP etc) | TCP |
