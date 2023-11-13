# Networking Operations of Menhera.org

**Languages**: **English**
| [Japanese (日本語)](/ja/)

`nc.menhera.org` is the domain for Network Operations of Menhera.org (Human-life Information Platforms Institute).

* [Menhera.org network backbone](backbone.html)
* [BGP Looking Glass](https://looking-glass.nc.menhera.org/)

## Managing Network resources

Menhera.org has the autonomous system number (ASN), AS63806.
It has also IPv4 and IPv6 address prefixes, called together **MENHERA-NET**.

_MENHERA-NET_ prefixes:

| IP version | Prefix |
|------------|--------|
| IPv4       | 43.228.174.0/24 |
| IPv6       | 2001:0df3:14c0::/48 |

### DNS domain names

Obviously, `menhera.org.` is our main domain. `menhera.com.` is used by some internal services.

We also have `menhera.or.jp.` (Japanese corporate domain) and `menhera.jp` (short .JP domain).

We use `*.menhera.io.` subdomains for hosting our users' websites.

### DNS authoritative servers

Normally, authoritative servers for our domains are ns01.menhera.org, ns02.menhera.org and ns03.menhera.org.

## Policy

See [Policy](policy.html).
