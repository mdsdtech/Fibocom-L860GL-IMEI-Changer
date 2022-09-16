# DIY Modem Tools

## Fibocom L850/L860
### IMEI Changer
- [Fibocom L860](https://github.com/mdsdtech/Fibocom-L860GL-IMEI-Changer/releases)
### Network Information Tools
#### Installation
```shell
curl -sLo /usr/bin/xmm75xx-info "https://raw.githubusercontent.com/lutfailham96/diy-modem-tools/main/xmm75xx/xmm75xx-info" && chmod +x /usr/bin/xmm75xx-info
```
#### How to use
- Execute
```
xmm75xx-info
```
- With custom interval
```
xmm75xx-info -i 3
```
- With custom device port
```
xmm75xx-info -d /dev/ttyACM2
```
- Example result
<p align="center">
  <img src="https://i.ibb.co/j5DXHFg/Screenshot-from-2022-03-07-08-39-33.png" />
</p>
