# Networking Operations of Menhera.org

**Languages**: **Japanese (日本語)**
| [English](/)

* [法人サイト: www.menhera.or.jp](https://www.menhera.or.jp/)
* [プロジェクトサイト (英語): www.menhera.org](https://www.menhera.org/)

`nc.menhera.org` Menhera.org (一般社団法人生活情報基盤研究機構) のネットワーク・オペレーションズ・センター (NOC) のドメインです。

* [Menhera.org ネットワークバックボーン](backbone.html)
* [BGP Looking Glass](https://looking-glass.nc.menhera.org/)

## 管理するネットワーク資源

Menhera.org は自律システム番号 (ASN)， AS63806 (**MENHERA**) を持ちます。
それはまた IPv4 と IPv6 のアドレス プレフィックスたちを持ち，それらのネットワークは一緒に **MENHERA-NET** と呼ばれています。

_MENHERA-NET_ のプレフィックスたち：

| IP バージョン | プレフィックス |
|------------|--------|
| IPv4       | 43.228.174.0/24 |
| IPv6       | 2001:0df3:14c0::/48 |

### 組織からのトラフィックを識別する

#### 信用されるトラフィックと信用すべきでないトラフィック

以下の IP 範囲はゲストおよび隔離されたネットワークサービス用ですので，
Menhera.org からのアクセスのみを許可したい場合はこれらをホワイトリストから取り除いてください。

私たちはまた，これらの IP アドレスからメールを送信することはありません。
私たちの側では，これらからの外向きのポート25番をブロックしています。

| Purpose | IPv4 | IPv6 |
|---------|------|------|
| ゲスト | 43.228.174.224/28 | 2001:0df3:14c0:fe00::/56 |
| 隔離されたネットワークサービス | 43.228.174.240/28 | 2001:0df3:14c0:ff00::/56 |

### DNS ドメイン名

明らかに， `menhera.org.` は私たちのメインのドメインです。 `menhera.com.` はいくらかの内部サービスで使われています。

私たちはまた `menhera.or.jp.` (日本の法人ドメイン) と `menhera.jp` (短かい .JP ドメイン) を持ちます。

私たちは `*.menhera.io.` サブドメインをユーザのウェブサイトをホストするのに使っています。

### DNS 権威サーバ

通常，私たちのドメインに対する権威サーバは， ns01.menhera.org， ns02.menhera.org そして ns03.menhera.org です。

## ポリシー

[ポリシー](policy.html) を見てください。
