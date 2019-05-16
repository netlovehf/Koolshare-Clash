<h1 align="center">
    <img src="https://koolclash.js.org/img/koolclash.png" alt="Clash" width="150">
    <br>KoolClash
</h1>

<p align="center">
一个运行在 Koolshare OpenWrt/LEDE 的 <a href="https://github.com/Dreamacro/clash" target="_blank">Clash</a> 客户端.<br>
<a href="https://koolclash.js.org">文档</a> |
<a href="https://github.com/SukkaW/Koolshare-Clash/releases">下载</a>
</p>

<p align="center">
    <!--<a href="https://travis-ci.org/SukkaW/KoolShare-Clash">
        <img src="https://img.shields.io/travis/SukkaW/KoolShare-Clash.svg?style=flat-square" alt="Travis-CI">
    </a>-->
    <a href="https://skk.moe" target="_blank"><img alt="Author" src="https://img.shields.io/badge/Author-Sukka-b68469.svg?style=flat-square"/></a>
    <a href="https://github.com/SukkaW/Koolshare-Clash/releases" target="_blank"><img src="https://img.shields.io/github/release/SukkaW/Koolshare-Clash/all.svg?style=flat-square"></a>
    <a href="https://github.com/Dreamacro/clash" target="_blank"><img src="https://img.shields.io/badge/Clash-0.14.0-1c4070.svg?style=flat-square"/></a>
    <a href="https://github.com/SukkaW/Koolshare-Clash/blob/master/LICENSE"><img src="https://img.shields.io/github/license/sukkaw/koolshare-clash.svg?style=flat-square"/></a>
</p>

<p align="center">
    <img src="https://i.loli.net/2019/04/16/5cb5e4b579a44.png">
</p>

> KoolClash 仅可以在 Koolshare OpenWrt/LEDE x86_64 上使用。如果你使用的是原版 OpenWrt，请使用 [Clash for OpenWrt](https://github.com/frainzy1477/clash/)。

## 名词解释

- Clash：一个 GO 开发的、基于规则的多平台代理客户端，兼容 Shadowsocks、V2Ray 等协议，拥有像 Surge 一样强大的代理规则。[GitHub](https://github.com/Dreamacro/clash)
- KoolClash：KoolClash 是 Clash 在 Koolshare OpenWrt/LEDE 上的客户端。[GitHub](https://github.com/SukkaW/Koolshare-Clash)

## 特性

- 使用 HTTP/HTTPS and SOCKS
- 和 Surge 相似的配置
- 支持基于地域的规则
- 支持 Vmess/Shadowsocks/Socks5 服务端协议
- 支持基于 Netfilter TCP 流量重定向

除了 Clash 的这些特性，KoolClash 有以下特性:

- 在 [Koolshare OpenWrt/LEDE X86](https://firmware.koolshare.cn/LEDE_X64_fw867/) 上安装、上传配置并运行 Clash
- 和 Surge 增强模式类似的代理网关

## 安装

请阅读 [文档 - 安装](https://koolclash.js.org/#/install)

## 构建

```bash
$ https://github.com/SukkaW/Koolshare-Clash
$ cd Koolshare-Clash
$ ./build # Get usage information
$ ./build pack # Build the package
$ ./build ipdb # Update Country.mmdb to latest
$ ./build dashboard # Update clash-dashboard to latest
```

## Clash 在其它平台上的客户端

- [Clash for Windows](https://github.com/Fndroid/clash_for_windows_pkg) : Clash 的 Windows 图形界面
- [clashX](https://github.com/yichengchen/clashX) : Clash 的 macOS 图形界面客户端
- [ClashA](https://github.com/ccg2018/ClashA) : Clash 的 Android 图形界面
- [Clash for OpenWrt](https://github.com/frainzy1477/clash) : Clash 在 OpenWrt 上的客户端

## 贡献

[汇报 Bug](https://github.com/SukkaW/Koolshare-Clash/issues/new/choose) | [改善文档](https://github.com/SukkaW/Koolshare-Clash/tree/master/docs) | [Fork & Open a New PR](https://github.com/SukkaW/Koolshare-Clash/fork)

欢迎一切贡献，包括但不限于增强、新特性、文档和代码的改进、Bug 汇报。

## 开源许可证

KoolClash 使用 GPL-3.0 协议开源 - 阅读项目的 [LICENSE](https://github.com/SukkaW/Koolshare-Clash/blob/master/LICENSE) 文件。

同时，这个项目中还包含了由 [MaxMind](https://www.maxmind.com) 提供的 [GeoLite2](https://dev.maxmind.com/geoip/geoip2/geolite2/)。

## 赞助

[![Dler Cloud](https://img.vim-cn.com/7e/dbc9122a41f7eadbab889a9037ef6232cbea51.png)](https://dlercloud.me)

## 维护者

**KoolClash** © [Sukka](https://github.com/SukkaW), Released under the [GPL-3.0]([./LICENSE](https://github.com/SukkaW/Koolshare-Clash/blob/master/LICENSE)) License.<br>
Authored and maintained by [Sukka]([Sukka](https://github.com/SukkaW)) with help from contributors ([list](https://github.com/SukkaW/Koolshare-Clash/contributors)).

> [Personal Website](https://skk.moe) · [Blog](https://blog.skk.moe) · GitHub [@SukkaW](https://github.com/SukkaW) · Telegram Channel [@SukkaChannel](https://t.me/SukkaChannel) · Twitter [@isukkaw](https://twitter.com/isukkaw) · Keybase [@sukka](https://keybase.io/sukka)
