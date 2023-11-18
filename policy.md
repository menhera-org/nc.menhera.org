# Policy

Languages: **English**
| [Japanese (日本語)](/ja/policy.html)

* [Top](/)

## AS peering policy

Our peering policy is Selective.

We hope that we can peer with many other organizations, but we are a nonprofit and have limited resources.

### Technical requirements

#### Mandatory

- You have a globally routable ASN.
- You can peer with us with both IPv4 and IPv6.

#### Recommended

- Routes you advertise should be able to be validated with ROAs/RPKI.

### Operational requirements

- You have registered necessary information on PeeringDB or alternatives.
- You have registered necessary objects on IRR(s).
- You can be contacted regarding operational affairs in a rapid manner.

### Traffic requirements

There is no specific requirements.

### Connection requirements

We can only provide peering with the following confitions:

- Tunneling over the Internet (IPv4 or IPv6).
- Tunneling using IPv6 and the regional network provided by NTT East (NGN).

Tunneling methods preferred: EtherIP over IPv6, GREtap over IPv6, GENEVE over IPv6.

### Routing policy

- We advertise the AS-Set AS-MENHERA.
- Prefixes smaller than the minimum (/24 for IPv4 and /48 for IPv6) are ignored upon receipt.
- We discard default routes and Bogons.
- We filter routing information using RPKI/ROV.

### End of peering

- We may end a peering when the conditions are no longer met or there is a serious threat to the stability of our network.
