# Menhera.org Network Backbone

* [Top](/)
* [BGP Looking Glass](https://looking-glass.nc.menhera.org/)

![Backbone](/assets/img/backbone-map.png)

## Weathermap

### Backbone

![Backbone Weathermap](https://librenms.menhera.org/pub/weathermap/backbone.svg)

### Tsuchiura (t)

![Backbone Weathermap](https://librenms.menhera.org/pub/weathermap/tsuchiura.svg)

### Chofu (c)

![Backbone Weathermap](https://librenms.menhera.org/pub/weathermap/chofu.svg)

## MTU sizes
Our network is interconnected with tunneling technologies.

* BGP backbone has the MTU size of 1500.
* (For Menhera.org users) Internal intranet links are encrypted, so they have MTU sizes varying from 1280 to 1372.
* In whatever case, MTU is never smaller than 1280, the IPv6 limit.
