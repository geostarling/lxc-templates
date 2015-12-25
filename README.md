LXC Templates
=============

Please note that in case of `lxc.network.type = none` setting on your guest, host's tcp and unix sockets are shared with guests. To avoid X server's socket collisions start X server on your guest with different display number e.g. like this: `start -- :2`
