# minieap for OpenWrt

## Build

First download [OpenWrt SDK](https://downloads.openwrt.org/) for your device.

```sh
cd /path/to/your/sdk
```
```sh
git clone https://github.com/MySelections/openwrt-minieap.git -b s0pt package/minieap
```
or 
```sh
git clone git@github.com:MySelections/openwrt-minieap.git -b s0pt package/minieap
```
```sh
make menuconfig # choose `minieap` in section `Network`
```
```sh
make package/minieap/compile V=s
```
