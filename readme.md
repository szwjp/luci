# luci

自维护的 OpenWrt / ImmortalWrt apk 软件包索引。

每个目录对应一个软件，目录中的 apk 可直接供 ImageBuilder 引用。界面包与中文语言包通常成对出现。

---

## argon

Argon 主题。

- `luci-theme-argon` — 现代化 LuCI 主题
- `luci-app-argon-config` — 主题外观设置界面
- `luci-i18n-argon-config-zh-cn` — 设置界面中文语言包

## aurora

Aurora 极光主题。

- `luci-theme-aurora` — 极光风格 LuCI 主题
- `luci-app-aurora-config` — 主题外观设置界面
- `luci-i18n-aurora-config-zh-cn` — 设置界面中文语言包

## bandix

实时流量监控。

- `bandix` — 采集与统计后端
- `luci-app-bandix` — 流量看板界面
- `luci-i18n-bandix-zh-cn` — 界面中文语言包

## clashoo

基于 mihomo / sing-box 的代理工具。

- `clashoo` — 代理后端
- `luci-app-clashoo` — 管理界面
- `luci-i18n-clashoo-zh-cn` — 界面中文语言包

## daed

基于 eBPF 的透明代理。

- `daed` — eBPF 透明代理后端
- `luci-app-daed` — 管理界面
- `luci-i18n-daed-zh-cn` — 界面中文语言包
- `v2ray-geoip` — IP 分流数据
- `v2ray-geosite` — 域名分流数据
- `vmlinux-btf` — 内核 BTF 信息，eBPF 运行所需

## homeproxy

基于 sing-box 的代理工具。

- `luci-app-homeproxy` — 管理界面
- `luci-i18n-homeproxy-zh-cn` — 界面中文语言包

## hysteria

- `hysteria` — 基于 QUIC 的代理内核

## ipsec-vpnd

IPSec VPN 服务端，基于 strongswan。

- `luci-app-ipsec-vpnd` — 服务端管理界面
- `luci-i18n-ipsec-vpnd-zh-cn` — 界面中文语言包
- `strongswan-minimal` — strongswan 元包
- `strongswan-mod-des` — DES 加密插件
- `strongswan-mod-kernel-libipsec` — 内核 libipsec 插件
- `strongswan-mod-xauth-generic` — XAUTH 认证插件
- `kmod-tun` — TUN/TAP 内核模块

## luci-app-quickstart

首页概览与网络配置向导。

- `luci-app-quickstart` — 首页与向导界面
- `luci-i18n-quickstart-zh-cn` — 界面中文语言包
- `quickstart` — 后端服务

## luci-app-run

- `luci-app-run` — 自定义脚本运行与开机自启管理

## luci-app-store

iStore 应用商店。

- `luci-app-store` — 应用商店界面
- `taskd` — 后台任务守护进程
- `luci-lib-taskd` — 任务调度库
- `luci-lib-xterm` — 网页终端组件

## lucky

端口转发、反向代理与动态域名。

- `lucky` — 后端服务
- `luci-app-lucky` — 管理界面
- `luci-i18n-lucky-zh-cn` — 界面中文语言包

## mihomo

- `mihomo` — Clash.Meta 代理内核

## nikki

基于 mihomo 的代理工具。

- `nikki` — 代理后端
- `luci-app-nikki` — 管理界面
- `luci-i18n-nikki-zh-cn` — 界面中文语言包

## openvpn-server

OpenVPN 服务端。

- `luci-app-openvpn-server` — 服务端管理界面
- `luci-i18n-openvpn-server-zh-cn` — 界面中文语言包

## openwrt-daede

基于 eBPF 的透明代理，dae / daed 双后端。

- `dae` — dae 后端
- `daed` — daed 后端
- `luci-app-daede` — 管理界面
- `vmlinux-btf` — 内核 BTF 信息，eBPF 运行所需

## partexp

- `luci-app-partexp` — 存储分区扩容工具
- `luci-i18n-partexp-zh-cn` — 界面中文语言包

## passwall

代理工具及其运行时依赖。

- `luci-app-passwall` — 管理界面
- `luci-i18n-passwall-zh-cn` — 界面中文语言包
- `chinadns-ng` — DNS 分流与防污染
- `dns2socks` — 通过 socks5 转发 DNS 查询
- `geoview` — geo 数据文件工具箱
- `tcping` — TCP 端口连通性探测
- `v2ray-geoip` — IP 分流数据
- `v2ray-geosite` — 域名分流数据

## passwall2

代理工具（第二代）。

- `luci-app-passwall2` — 管理界面
- `luci-i18n-passwall2-zh-cn` — 界面中文语言包

## pwcore

PassWall 运行核心备用件。

- `geoview` — geo 数据文件工具箱
- `hysteria` — 基于 QUIC 的代理内核

## quickfile

Web 文件管理器。

- `quickfile` — 文件服务后端
- `luci-app-quickfile` — 管理界面
- `luci-i18n-quickfile-zh-cn` — 界面中文语言包

## rtp2httpd

IPTV 组播流转 HTTP 单播。

- `rtp2httpd` — 转发服务后端
- `luci-app-rtp2httpd` — 管理界面
- `luci-i18n-rtp2httpd-zh-cn` — 界面中文语言包

## sing-box

- `sing-box` — 通用代理内核

## ssrp

SSR Plus 代理工具及其运行时依赖。

- `luci-app-ssr-plus` — 管理界面
- `luci-i18n-ssr-plus-zh-cn` — 界面中文语言包
- `shadowsocksr-libev-ssr-local` — 本地 socks5 代理模式
- `shadowsocksr-libev-ssr-redir` — 透明代理（TCP 重定向）模式
- `shadowsocksr-libev-ssr-nat` — 透明代理（NAT）模式
- `shadowsocksr-libev-ssr-server` — 服务端模式
- `shadowsocksr-libev-ssr-check` — 节点可用性检测
- `naiveproxy` — 基于 Chromium 网络栈的代理
- `dns2tcp` — DNS 查询由 UDP 转 TCP
- `ipt2socks` — 透明代理流量转 socks5
- `lua-neturl` — Lua URL 解析库

## taskplan

- `luci-app-taskplan` — 计划任务（cron）管理
- `luci-i18n-taskplan-zh-cn` — 界面中文语言包

## turboacc

- `luci-app-turboacc` — 网络加速（BBR、流量分载、全锥形 NAT）
- `luci-i18n-turboacc-zh-cn` — 界面中文语言包

## xray-core

- `xray-core` — Xray 代理内核
