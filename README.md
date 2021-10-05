# minieap for OpenWrt

## Build

First download [OpenWrt SDK](https://downloads.openwrt.org/) or [PandoraBox SDK](http://downloads.pangubox.com:6380/pandorabox/) for your device.

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
make menuconfig # choose `minieap` to [M] in section `Network`
make package/minieap/compile V=s
```
