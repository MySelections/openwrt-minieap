# minieap for OpenWrt

## Build

First download [OpenWrt SDK](https://downloads.openwrt.org/) for your device.

```sh

"cd /path/to/your/sdk"
"git clone https://github.com/MySelections/openwrt-minieap.git -b s0pt package/minieap"
or "git clone git@github.com:MySelections/openwrt-minieap.git -b s0pt package/minieap"
"make menuconfig" # choose `minieap` in section `Network`
"make package/minieap/compile V=s"
```
