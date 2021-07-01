
# Unbound

An Unbound configuration file setup for encrypting all outbound DNS requests through Cloudflare's DNS over TLS (DoT) public name servers.  

---

**Pre-configured forwarding addresses (IPv4 and IPv6):**
- forward-addr: 1.1.1.1@853 #cloudflare-dns.com
- forward-addr: 1.0.0.1@853 #cloudflare-dns.com
- forward-addr: 2606:4700:4700::1111@853 #cloudflare-dns.com
- forward-addr: 2606:4700:4700::1001@853 #cloudflare-dns.com

**Optional forwarding addresses (IPv4 and IPv6):**
- forward-addr: 8.8.8.8@853 #dns.google
- forward-addr: 8.8.4.4@853 #dns.google
- forward-addr: 2001:4860:4860::8888@853 #dns.google
- forward-addr: 2001:4860:4860::8844@853 #dns.google
- forward-addr: 9.9.9.9@853 #dns.quad9.net
- forward-addr: 149.112.112.112@853 #dns.quad9.net
- forward-addr: 2620:fe::fe@853 #dns.quad9.net
- forward-addr: 2620:fe::9@853 #dns.quad9.net
- forward-addr: 9.9.9.10@853 #dns-nosec.quad9.net
- forward-addr: 149.112.112.10@853 #dns-nosec.quad9.net
- forward-addr: 2620:fe::10@853 #dns-nosec.quad9.net
- forward-addr: 2620:fe::fe:10@853 #dns-nosec.quad9.net
- forward-addr: 9.9.9.11@853 #dns11.quad9.net
- forward-addr: 149.112.112.11@853 #dns11.quad9.net
- forward-addr: 2620:fe::11@853 #dns11.quad9.net
- forward-addr: 2620:fe::fe:11@853 #dns11.quad9.net

## Setup, DNS Leak, and DNSSEC Tests:

- [Cloudflare Test (1.1.1.1)](https://1.1.1.1/help)
- [DNS Leak Test #1](https://www.dnsleaktest.com/)
- [DNS Leak Test #2](https://ipleak.net/)
- [DNSSEC Test](https://dnssec.vs.uni-due.de/)

## Upcoming Changes

In the future I will be incoporating localized adblocking functionality, similiar to Pi-Hole, all through Unbound. Stay tuned.