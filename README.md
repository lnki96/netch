# Netch
[![](https://img.shields.io/badge/Telegram-Channel-blue)](https://t.me/Netch) [![](https://img.shields.io/badge/Telegram-Group-green)](https://t.me/Netch_Discuss_Group) ![GitHub Actions & Netch CI](https://github.com/NetchX/Netch/workflows/GitHub%20Actions%20&%20Netch%20CI/badge.svg)
          
Game accelerator

[简体中文](docs/README.zh-CN.md) (此版本内容更丰富)

## TOC
- [Netch](#netch)
	- [TOC](#toc)
	- [Description](#description)
	- [Donate](#donate)
	- [Sponsor](#sponsor)
	- [Screenshots](#screenshots)
	- [Requirements](#requirements)

## Description

Netch is an open source game accelerator. Unlike SSTap, which needs to add rules to function as a blacklist proxy, Netch is more similar to SocksCap64, which can scan the game directory to get their process names specifically and forward their network traffic through the proxy server. Now supports Socks5, Shadowsocks, ShadowsocksR, VMess.

As well, Netch avoid the restricted NAT problem caused by SSTap. You can use an NATTypeTester to test out what your NAT type is. When using SSTap to speed up some P2P gaming connections or the game is required for that kind of open NAT type, you may experience some bad situations such as unable to join the game.

## Donate
- XMR *48ju3ELNZEa6wwPBMexCJ9G218BGY2XwhH6B6bmkFuJ3QgM4hPw2Pra35jPtuBZSc7SLNWeBpiWJZWjQeMAiLnTx2tH2Efx*

## Sponsor
开发不易，以下为恰饭时间

[![NyanCAT](docs/sponsor/nyancat.jpg)](https://nyancat.info)

NyanCAT Network，全中转高质量节点，多条低倍率节点保证流量无忧，节点极低延迟涵盖五大洲。Netflix 视频党，游戏党，海外回国党必备，无需年付，月付 19 元起

[![ManSora](docs/sponsor/mansora.jpg)](https://www.mansora.net/cart.php)

## Screenshots
![](docs/screenshots/main.png)

## Requirements
- Microsoft Visual C++ Runtime
- [.NET Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework/net48)

## Quote
- [go-tun2socks](https://github.com/eycorsican/go-tun2socks)
- [shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev)
- [shadowsocksr-libev](https://github.com/shadowsocksrr/shadowsocksr-libev)
- [v2ray-core](https://github.com/v2ray/v2ray-core)
- [ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)
- [dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)
- [unbound](https://github.com/NLnetLabs/unbound)
- [tap-windows6](https://github.com/OpenVPN/tap-windows6)
- [Privoxy](https://www.privoxy.org/)
- [NatTypeTester](https://github.com/HMBSbige/NatTypeTester)
- [NetFilter SDK](https://netfiltersdk.com/)
