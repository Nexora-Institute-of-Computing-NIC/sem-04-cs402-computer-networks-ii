# CS402 — Computer Networks II — PLAN

**Semester:** 4 · **Credits:** 4 · **Level:** Intermediate-Advanced
**Theory:** 45 hrs · **Lab:** 30 hrs · **Tools:** Wireshark, iptables, OpenVPN, nginx, mininet

## Syllabus

### Unit 1 — Advanced Routing (9 lectures)
1. Routing protocols revisited — interior vs exterior
2. RIP — distance-vector in depth
3. OSPF — link-state, areas, LSAs
4. BGP — path-vector and the global Internet
5. Autonomous systems and peering
6. Policy routing and route maps
7. Multicast routing — IGMP, PIM (overview)
8. MPLS — labels and traffic engineering (overview)
9. Software-defined networking — the control plane revolution

### Unit 2 — Network Security Fundamentals (9 lectures)
1. Threat models — attackers and attack surfaces
2. Symmetric encryption — AES, block vs stream
3. Asymmetric encryption — RSA, elliptic curves
4. Hash functions and message authentication codes
5. TLS — the handshake, certificates, and trust
6. VPNs — IPsec and WireGuard
7. Firewalls — packet filter, stateful, application
8. Intrusion detection and prevention systems
9. Security best practices — defence in depth

### Unit 3 — Wireless and Mobile Networks (9 lectures)
1. Wireless fundamentals — radio, interference, bands
2. Wi-Fi — 802.11 standards, channels, security (WPA2, WPA3)
3. Bluetooth and BLE — use cases
4. Cellular networks — 4G, 5G architecture
5. Mobile IP and handoff
6. Ad-hoc and mesh networks
7. IoT networking — MQTT, CoAP, LoRaWAN
8. Wireless security threats
9. Emerging — 6G, satellite Internet

### Unit 4 — Performance and Quality of Service (9 lectures)
1. Latency, jitter, bandwidth, throughput
2. Queuing disciplines — FIFO, priority, weighted fair
3. Congestion control revisited — TCP variants and BBR
4. Traffic shaping and policing
5. QoS — DiffServ and IntServ
6. Load balancing — L4 vs L7
7. Content delivery networks (CDNs)
8. Caching strategies — HTTP cache, DNS, edge
9. Network monitoring and observability

### Unit 5 — Modern Internet Architecture (9 lectures)
1. HTTP/2 and HTTP/3 — multiplexing, QUIC
2. DNS over HTTPS and DNS over TLS
3. gRPC and HTTP/2 streaming
4. WebSocket and real-time protocols
5. Peer-to-peer networks — BitTorrent, IPFS
6. Cloud networking — VPCs, subnets, NAT gateways
7. Container networking — bridge, overlay, CNI
8. Service mesh — Istio, Envoy (conceptual)
9. Network automation — Ansible, Terraform basics

## Practical Labs (18)

1. Configure static routes and inspect the routing table
2. Set up OSPF in mininet — verify convergence
3. Read BGP tables with `bgp.he.net` and interpret AS paths
4. Configure a Linux firewall with iptables
5. Set up nftables — modern firewall rules
6. Demonstrate TLS with `openssl s_client`
7. Create a self-signed certificate and use it in nginx
8. Set up a WireGuard VPN between two machines
9. Analyse WPA2 handshake in Wireshark (capture on a test AP)
10. Build a Wi-Fi hotspot and inspect client behaviour
11. Simulate 5G core signalling (conceptual lab)
12. Implement a QoS shaper with `tc`
13. Set up nginx as a load balancer with upstream pools
14. Cache static content with nginx `proxy_cache`
15. Configure a CDN using Cloudflare's free tier on a test site
16. Trace a gRPC call with `grpcurl`
17. Inspect container networking with `docker network`
18. Automate network changes with Ansible

## Assignments

1. Routing comparison — analyse OSPF and BGP on a test topology
2. Security audit — review TLS configuration of 5 real sites
3. Wireless survey — analyse coverage and interference
4. Performance analysis — measure and compare HTTP/1.1, HTTP/2, HTTP/3
5. Modern architecture writeup — design a network for a small cloud app
