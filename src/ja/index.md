---
title: AS63806 NOC トップ
description: 一般社団法人生活情報基盤研究機構 (Menhera) によって運用されている、AS63806 Menhera®のホームページです。
lang: ja
---

**Languages**: **Japanese (日本語)**
| [English](/)

`menhera.ad.jp` はMenhera® (一般社団法人生活情報基盤研究機構) のネットワーク・オペレーションズ・センター (NOC) のドメインです。Menhera® は JPNIC における IPアドレス管理指定事業者 (LIR) です。私たちはまた、届出電気通信事業者の取得に向け準備しています。

* [Menhera® ネットワークバックボーン](backbone.html)
* [BGP Looking Glass](https://looking-glass.nc.menhera.org/)

## 管理するネットワーク資源

Menhera® は自律システム番号 (ASN)， AS63806 (**MENHERA**) を持ちます。
それはまた IPv4 と IPv6 のアドレス プレフィックスたちを持ち，それらのネットワークは一緒に **MENHERA-NET** と呼ばれています。

_MENHERA-NET_ のプレフィックスたち：

| IP バージョン | プレフィックス |
|------------|--------|
| IPv4       | `43.228.174.0/24`, `123.253.119.0/24` |
| IPv6       | `2402:3160::/32-/48` |

### 組織からのトラフィックを識別する

#### 信用されるトラフィックと信用すべきでないトラフィック

以下の IP 範囲はゲストおよび隔離されたネットワークサービス用ですので，
Menhera® からのアクセスのみを許可したい場合はこれらをホワイトリストから取り除いてください。

私たちはまた，これらの IP アドレスからメールを送信することはありません。
私たちの側では，これらからの外向きのポート25番をブロックしています。

| Purpose | IPv4 | IPv6 |
|---------|------|------|
| ゲスト | 43.228.174.224/28 | 2402:3160:e00::/40 |
| 隔離されたネットワークサービス | 43.228.174.240/28 | 2402:3160:f00::/40 |

### DNS ドメイン名

こちらが網羅的ではありませんが、私たちが管理する DNS ドメイン名の短かいリストです。

| DNS Domain Name | Description |
|-----------------|-------------|
| `menhera.org.` | Project website, branding |
| `menhera.com.` | Google Workspace, branding |
| `menhera.ad.jp.` | LIR Portal, Google Workspace |
| `menhera.or.jp.` | Japanese corporate website |
| `menhera.jp.` | Short .JP domain, redirect |
| `mdns.jp.` | MDNS.JP Authoritative DNS |
| `mnhr.org.` | URL Shortener |

### DNS 権威サーバ

通常，私たちのドメインに対する権威サーバは， `mdns.jp` からのものです。

## MAC Address

私たちはIEEEからMACアドレスの割り当てを受けています。

| range | start | end |
|-------|-------|-----|
| `60:a4:34:4x:xx:xx` | `60:a4:34:40:00:00` | `60:a4:34:4f:ff:ff` |

この範囲からのMACアドレスをIXPのポート等で利用することがあります。

## ポリシー

[ポリシー](policy.html) を見てください。

## 更新情報

- 2025-10: 私たちはJPNICでIPアドレス管理指定事業者（LIR）になりました。
- 2024-07-20: 新しい上流事業者 AS150369 (Infal TelHi) と接続しました。 

## メンテナンスとネットワーク障害情報

[Menhera® Status](https://status.menhera.org/)
