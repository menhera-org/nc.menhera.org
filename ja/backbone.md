# Menhera.org ネットワークバックボーン

* [トップ](/ja/)
* [BGP Looking Glass](https://looking-glass.nc.menhera.org/)

![Backbone](/assets/img/backbone-map.png)

## Weathermap

### バックボーン

![Backbone Weathermap](https://librenms.menhera.org/pub/weathermap/backbone.svg)

### 土浦 (t)

![Backbone Weathermap](https://librenms.menhera.org/pub/weathermap/tsuchiura.svg)

### 調布 (c)

![Backbone Weathermap](https://librenms.menhera.org/pub/weathermap/chofu.svg)

## MTU サイズ
私たちのネットワークはトンネリング技術を使用して相互接続しています。

* BGP バックボーンは，1500のMTUサイズを持ちます。
* (Menhera.org の利用者向け) 内部のイントラネット接続は暗号化されていて， 1280 から 1372 までの MTU を持ちます。
* どんな場合でも，IPv6 の最小である 1280 を MTU が下回ることはありません。
