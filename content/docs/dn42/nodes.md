---
weight: 10
title: Nodes
bookToc: false
---

# Nodes

Connection via v6 (and v6 DNS) is always preferred, as I don't control the IPv4 space (yet™). If I ever decide to move the nodes, I'll be able to move it along with the v6 address.

| Name              | Location      | Provider | Wireguard pubkey                             | Wireguard port                  | IPv6 Link-Local  |
|-------------------|---------------|----------|----------------------------------------------|---------------------------------|------------------|
| ams1.as199680.net | Amsterdam, NL | iFog     | /2PiRi0hn4ZpCX2Kfu9+/pLw6tOwC09nO1VBP/FywkM= | Customized (set during peering) | fe80::9680:64/64 |
| lux1.as199680.net | Bissen, LU    | BuyVM    | to be added                                  | Customized (set during peering) | to be added      |
| waw1.as199680.net | Warsaw, PL    | Vultr    | to be added                                  | Customized (set during peering) | to be added      |


| Name              | IPv4            | v4 DNS               | IPv6              | v6 DNS               |
|-------------------|-----------------|----------------------|-------------------|----------------------|
| ams1.as199680.net | 193.148.248.149 | v4.ams1.as199680.net | 2a05:dfc7:9000::1 | v6.ams1.as199680.net |
| lux1.as199680.net | 104.244.79.85   | v4.lux1.as199680.net | 2a05:dfc7:9001::1 | v6.lux1.as199680.net |
| waw1.as199680.net | 70.34.250.15    | v4.waw1.as199680.net | 2a05:dfc7:9002::1 | v6.waw1.as199680.net |