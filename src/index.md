---
title: AS63806 NOC Top
description: This is the homepage for AS63806 Menhera®, operated by the Human-life Information Platforms Institute (Menhera).
lang: en
---

**Languages**: **English**
| [Japanese (日本語)](/ja/)

`menhera.ad.jp` is the domain for Network Operations of Menhera® (Human-life Information Platforms Institute). Menhera® is an 'IP Address Management Agent' (LIR) at JPNIC. We are
actively preparing for a Reported Telecommunication Carrier
(届出電気通信事業者) status in Japan.

* [Menhera® network backbone](backbone.html)
* [BGP Looking Glass](https://looking-glass.nc.menhera.org/)

## Managing Network resources

Menhera® has the autonomous system number (ASN), AS63806 (**MENHERA**).
It has also IPv4 and IPv6 address prefixes, called together **MENHERA-NET**.

_MENHERA-NET_ prefixes:

| IP version | Prefix |
|------------|--------|
| IPv4       | `43.228.174.0/24`, `123.253.119.0/24` |
| IPv6       | `2402:3160::/32-/48` |

### Recognizing traffic from the organization

#### Trusteed and untrusted traffic

The following IP ranges are for guests and isolated network services,
so please remove them from your whitelist if you only want to allow traffic from Menhera®.

We also do not send emails from these IP addresses.
On our side, we block outgoing port 25 from these IP addresses.

| Purpose | IPv4 | IPv6 |
|---------|------|------|
| Guests | 43.228.174.224/28 | 2402:3160:e00::/40 |
| Isolated networking services | 43.228.174.240/28 | 2402:3160:f00::/40 |

### DNS domain names

Here's the short non-exhaustive list of DNS domains we control:

| DNS Domain Name | Description |
|-----------------|-------------|
| `menhera.org.` | Project website, branding |
| `menhera.com.` | Google Workspace, branding |
| `menhera.ad.jp.` | LIR Portal, Google Workspace |
| `menhera.or.jp.` | Japanese corporate website |
| `menhera.jp.` | Short .JP domain, redirect |
| `mdns.jp.` | MDNS.JP Authoritative DNS |
| `mnhr.org.` | URL Shortener |

### DNS authoritative servers

Normally, authoritative servers for our domains are from `mdns.jp`.

## MAC Address

We have been assigned a MAC address block from IEEE:

| range | start | end |
|-------|-------|-----|
| `60:a4:34:4x:xx:xx` | `60:a4:34:40:00:00` | `60:a4:34:4f:ff:ff` |

We may use MAC addresses from this range on IXP ports, etc.

## Policy

See [Policy](policy.html).

## Updates

- 2025-10: We are now an IP Address Management Agent (LIR) at JPNIC.
- 2024-07-20: New upstream provider AS150369 (Infal TelHi) is now available and connected.

## Maintenance and network faults information

[Menhera® Status](https://status.menhera.org/)
