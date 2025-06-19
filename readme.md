# Various tools for OpenWRT

## asus-rt-ax89x/fan_control

Daemon for fan control on Asus RT-AX89X modded using Noctua NF-A9 (12 V) fan.

It supports stock fan optionally. To use with the stock fan, set in `fan_monitor`:

```
mod_fan=${mod_fan:-false}
```

