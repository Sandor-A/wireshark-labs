# Lab 02 – Basic Display Filters

## Objective
Use Wireshark display filters to isolate specific traffic.

## Common Filters
```
ip.addr == 192.168.1.1
tcp.port == 80
udp.port == 53
http
dns
```

## Practice
- Filter HTTP traffic
- Filter DNS queries
- Identify source and destination IPs

## SOC Perspective
Filtering allows analysts to quickly focus on relevant traffic during incident investigations.
