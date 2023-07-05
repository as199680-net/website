---
weight: 2
title: Peering policy
bookToc: false
---

# Peering policy
AS199680 has an generally open peering policy to all dual-stack, or v6-only networks. \
If you don't have a v6 space assigned on your end, it's time to make a pull request. \
Feel free to send me an email, and I'll happily set up the peering.

Send the following information to dn42@as199680.net:
* The as199680.net you'd like to peer with
* Your ASN
* The public address of your host - preferrably a DNS name
* The tunnel details (only wireguard supported):
    - Port number
    - Public key
    - IP address on your end of the tunnel - preferrably a Link-Local IPv6
* BGP features supported (MPBGP/Extended Next Hop)