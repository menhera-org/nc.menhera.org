# Networking Operations of Menhera.org

**Languages**: **English**
| [Japanese (日本語)](/ja/)

* [Corporate site (Japanese): www.menhera.or.jp](https://www.menhera.or.jp/)
* [Project site: www.menhera.org](https://www.menhera.org/)

`nc.menhera.org` is the domain for Network Operations of Menhera.org (Human-life Information Platforms Institute).

* [Menhera.org network backbone](backbone.html)
* [BGP Looking Glass](https://looking-glass.nc.menhera.org/)

## Managing Network resources

Menhera.org has the autonomous system number (ASN), AS63806 (**MENHERA**).
It has also IPv4 and IPv6 address prefixes, called together **MENHERA-NET**.

_MENHERA-NET_ prefixes:

| IP version | Prefix |
|------------|--------|
| IPv4       | 43.228.174.0/24 |
| IPv6       | 2001:0df3:14c0::/48 |

### Recognizing traffic from the organization

#### Trusteed and untrusted traffic

The following IP ranges are for guests and isolated network services,
so please remove them from your whitelist if you only want to allow traffic from Menhera.org.

We also do not send emails from these IP addresses.
On our side, we block outgoing port 25 from these IP addresses.

| Purpose | IPv4 | IPv6 |
|---------|------|------|
| Guests | 43.228.174.224/28 | 2001:0df3:14c0:fe00::/56 |
| Isolated networking services | 43.228.174.240/28 | 2001:0df3:14c0:ff00::/56 |

### DNS domain names

Obviously, `menhera.org.` is our main domain. `menhera.com.` is used by some internal services.

We also have `menhera.or.jp.` (Japanese corporate domain) and `menhera.jp` (short .JP domain).

We use `*.menhera.io.` subdomains for hosting our users' websites.

### DNS authoritative servers

Normally, authoritative servers for our domains are ns01.menhera.org, ns02.menhera.org and ns03.menhera.org.

## Policy

See [Policy](policy.html).

## Maintenance and network faults information

- Planned (as of April 2024): \[Maintenance\] The access line for Tsuchiura networks will be down for a short time, to update equipments. The date will be announced when determined.
- Planned (as of April 2024): \[Maintenance\] The site networks at Chofu will be down for a while to replace NICs of a router.
- 2024-04-06: \[Maintenance\] Upstream provider of Menhera.org (HOMENOC POP03) will be down for maintenance (1400-2000+0900) and this can affect our networks to cause short (up to 5 minutes) outage.
- 2024-03-31 to 2024-04-04: \[Fault\] Network configuration problems affecting our email servers prevented some email from reaching our users.
- 2024-03-30: \[Maintenance\] Servers at Tsuchiura (private ASN 65198) was unavailable due to switching networks.
- 2024-03-27: \[Fault\] Reorganizing certain parts of the network triggered buggy behavior in some routers, and traffic was disrupted for a while.
- 2024-03-25: \[Maintenance\] Reorganizing backbone connections disrupted some traffic for a while. This was done to make some redundancy in our networks.
- 2024-03-09: \[Fault\] A router at Tsuchiura failed and part of the network went down.
