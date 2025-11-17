# Networking Operations of Menhera.org

**Languages**: **English**
| [Japanese (日本語)](/ja/)

* [Corporate site (Japanese): www.menhera.or.jp](https://www.menhera.or.jp/)
* [Project site: www.menhera.org](https://www.menhera.org/)

`nc.menhera.org` is the domain for Network Operations of Menhera.org (Human-life Information Platforms Institute). Menhera.org is an 'IP Address Management Agent' (LIR) at JPNIC.

* [Menhera.org network backbone](backbone.html)
* [BGP Looking Glass](https://looking-glass.nc.menhera.org/)

## Managing Network resources

Menhera.org has the autonomous system number (ASN), AS63806 (**MENHERA**).
It has also IPv4 and IPv6 address prefixes, called together **MENHERA-NET**.

_MENHERA-NET_ prefixes:

| IP version | Prefix |
|------------|--------|
| IPv4       | `43.228.174.0/24`, `123.253.119.0/24` |
| IPv6       | `2402:3160::/32-/48` |

### Recognizing traffic from the organization

#### Trusteed and untrusted traffic

The following IP ranges are for guests and isolated network services,
so please remove them from your whitelist if you only want to allow traffic from Menhera.org.

We also do not send emails from these IP addresses.
On our side, we block outgoing port 25 from these IP addresses.

| Purpose | IPv4 | IPv6 |
|---------|------|------|
| Guests | 43.228.174.224/28 | 2402:3160:e00::/40 |
| Isolated networking services | 43.228.174.240/28 | 2402:3160:f00::/40 |

### DNS domain names

Obviously, `menhera.org.` is our main domain. `menhera.com.` is used by some internal services.

We also have `menhera.ad.jp.` (LIR domain, used for mailing), `menhera.or.jp.` (Japanese corporate domain) and `menhera.jp` (short .JP domain).

We use `*.menhera.io.` subdomains for hosting our users' websites.

### DNS authoritative servers

Normally, authoritative servers for our domains are from `mdns.jp`.

## Policy

See [Policy](policy.html).

## Updates
- 2024-07-20: New upstream provider AS150369 (Infal TelHi) is now available and connected.

## Maintenance and network faults information

[Menhera.org Status](https://status.menhera.org/)
