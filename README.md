# White IP checker for OpenWrt

If your ISP sometimes issues IP from [subnet](https://tools.ietf.org/html/rfc6598) ``100.64.0.0/10`` and you are using [OpenWrt](https://openwrt.org/) on your router, you can use this tiny script to automatically reconnect when this occurs 

## Usage
Just place ``30-check-white-ip`` to ``/etc/hotplug.d/iface/`` on your router

Enjoy!