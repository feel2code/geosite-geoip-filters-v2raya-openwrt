# geosite-geoip-filters-v2raya-openwrt

Small docpage for setting up v2raya on openwrt

## Installing

Please install `v2raya` and `luci-app-v2raya` packages in openwrt.

## Configuration

1. Import subscription of vless into v2raya web gui interface
2. Use `settings.png` as example for v2raya web gui settings
3. Use `routing-config.txt` in RoutingA config inside v2raya web gui
4. Put both files `geoip.ru` and `geosite.ru` into directory inside your openwrt `/usr/share/xray/`
5. Profit!
