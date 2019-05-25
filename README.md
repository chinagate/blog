### <p align="right">文件</a>

# 什么是<a href="https://github.com/TheTorProject">Tor</a>？

<a href="https://torchina.gitlab.io/get/tor.html">https://torchina.gitlab.io/get/tor.html</a>

<a href="https://tb-manual.torproject.org/zh-CN/about/">https://tb-manual.torproject.org/zh-CN/about/</a> | 防火墙

## 下面这张是 meek 的示意图:

![alt text](https://raw.githubusercontent.com/mjstest/orgb1/1ef2f755a195eef11312653ac59a63f5/meek-diagram.png?raw=true)

<p>从图中可以看出，meek 跟 obfsproxy 的主要差异在于：meek server 并不是直接暴露出来的。换句话说，你本机【不需要】直接连接 meek server，而是直接连接云计算平台的服务器（图中的“Frontend Server”）。
 如此一来，即便 GFW 知道 meek server 的 IP，并且封杀这些 IP，也【没有】意义。而云计算平台的 IP，GFW 又不敢封杀。这就是 meek 插件可以突破 GFW 的关键所在。</p>

<p align="right"><a href="https://torchina.gitlab.io/get/meek.html">英文文档</a></p>

## Tor浏览器版本8.5下载 | <a href="https://raw.githubusercontent.com/mjstest/orgb2/ce120a3d9d920acf4a155bc51fe7babd/sha256sums-signed-build.txt">SHA256校验和</a> | <a href="https://bitbucket.org/chinagate/files/downloads/tor-0.4.0.5.tar.gz">源代码</a> &middot; (<a href="https://raw.githubusercontent.com/mjstest/orgb2/626ea07c477b241efe3fd9fb8b1c4340/tor-0.4.0.5.tar.gz.asc">sig</a>)

### Windows

<a href="https://bitbucket.org/chinagate/tor/downloads/torbrowser-install-win64-8.5_zh-CN.exe">Tor浏览器64位</a> &middot; (<a href="https://raw.githubusercontent.com/mjstest/orgb2/d3bab7d2e1a79bb8d220cdcb40d40082/torbrowser-install-win64-8.5_zh-CN.exe.asc">sig</a>) | <a href="https://bitbucket.org/chinagate/tor/downloads/torbrowser-install-8.5_zh-CN.exe">32位</a> &middot; (<a href="https://raw.githubusercontent.com/mjstest/orgb2/a0343bff2a16482bd5d83a9c4492f8aa/torbrowser-install-8.5_zh-CN.exe.asc">sig</a>)</a><br>1d71bd4c2f93a1a7d81b57608c4f750bbcd4a48ee04a77be13ef372d543e4d34</br>

<a href="https://bitbucket.org/chinagate/tor/downloads/tor-win64-0.3.5.8.zip">专家束64位</a> &middot; (<a href="https://raw.githubusercontent.com/mjstest/orgb2/6be60f090b2f5a37cb2dde2d44164f1d/tor-win64-0.3.5.8.zip.asc">sig</a>) | <a href="https://bitbucket.org/chinagate/tor/downloads/tor-win32-0.3.5.8.zip">32位</a> &middot; (<a href="https://raw.githubusercontent.com/mjstest/orgb2/235e134fabb5a8c27016158f541f25c8/tor-win32-0.3.5.8.zip.asc">sig</a>)<br>f7f235fa24fb4b8dade69fd6ad6e09c53770be06af630ffc0ce9cc321f19c887</br>

### Linux

<a href="https://bitbucket.org/chinagate/tor/downloads/tor-browser-linux64-8.5_zh-CN.tar.xz">Tor浏览器64位</a> &middot; (<a href="https://raw.githubusercontent.com/mjstest/orgb2/00f90a12ff188990f43e4f4b18386518/tor-browser-linux64-8.5_zh-CN.tar.xz.asc">sig</a>) | <a href="https://bitbucket.org/chinagate/tor/downloads/tor-browser-linux32-8.5_zh-CN.tar.xz">32位</a> &middot; (<a href="https://raw.githubusercontent.com/mjstest/orgb2/1dbf5d46ff947fe1bb88b9a6633483a0/tor-browser-linux32-8.5_zh-CN.tar.xz.asc">sig</a>) <br>aebc74b309c8b506ec2b378f023747e67c3259f6551f9fec9ee350c52eb8ab37</br>

### Mac OS X

<a href="https://bitbucket.org/chinagate/tor/downloads/TorBrowser-8.5-osx64_zh-CN.dmg">Tor浏览器64位</a> &middot; (<a href="https://raw.githubusercontent.com/mjstest/orgb2/b8fa8fb607e26ec180fd4fd116fb9d0f/TorBrowser-8.5-osx64_zh-CN.dmg.asc">sig</a>) <br>f3d5ca2db08db3c612713b3416edf684b1681f3ad23df1ec79d9a662309edfa9</br>

### Android

<a href="https://bitbucket.org/chinagate/files/downloads/tor-browser-8.5a11-android-armv7-multi.apk">tor-browser-8.5a11-android-armv7-multi.apk</a> &middot; (armv7)<br>3B1E69233CF4DAFC36CF3D85B094B8582A4D197228C937E102483BB3F3AF75BB</br>

<a href="https://bitbucket.org/chinagate/files/downloads/tor-browser-8.5a11-android-x86-multi.apk">tor-browser-8.5a11-android-x86-multi.apk</a> &middot; (x86)<br>03E58CBC0EF6B3DA0A1C9577F7D956A6568B31585406061EA8AB15794BBE9BAE</br>

### Onion浏览器 | iOS

<a href="https://github.com/OnionBrowser/OnionBrowser">https://github.com/OnionBrowser/OnionBrowser</a><br>

## 配置

![alt text](https://raw.githubusercontent.com/mjstest/orgb1/a5b50a2a9f002c828e5f9437f4312e2e/config1.png)
<br>
<br>
![alt text](https://raw.githubusercontent.com/mjstest/orgb1/7ed2b337bd0c74a9db3d66befdecd87e/config2.png)
<br>
<br>
![alt text](https://raw.githubusercontent.com/mjstest/orgb1/59dcbecb86fed3242d2042a191fb529e/config3.png)

## 其他审查规避软件

#### <a href="https://github.com/shadowsocks">影梭 | shadowsocks</a>

<a href="https://torchina.gitlab.io/get/shadowsocks.html">https://torchina.gitlab.io/get/shadowsocks.html</a>

#### <a href="https://github.com/Psiphon-Labs">赛风 | Psiphon</a>

<a href="https://torchina.gitlab.io/get/psiphon.html">https://torchina.gitlab.io/get/psiphon.html</a>

## VPS设置和VPN服务

#### <a href="https://github.com/Bill0412/bandwagonhost-tutorial">bandwagonhost教程 | vps设置</a> | <a href="https://invidio.us/watch?v=cfh4BFbTDkU">手把手教你在搬瓦工VPS上搭建Shadowsocks服务实现科学上网</a> &middot; <a href="https://raw.githubusercontent.com/mjstest/orgb2/d539aa9f6d403d80ee221da1144ebc00/手把手教你在搬瓦工VPS上搭建Shadowsocks服务实现科学上网-cfh4BFbTDkU.mp4">下载视频</a>

<a href="https://invidio.us/search?q=bandwagonhost">https://invidio.us/search?q=bandwagonhost</a>

<a href="https://www.bandwagonhost.net">https://www.bandwagonhost.net</a>

#### <a href="https://github.com/StreisandEffect/streisand">Streisand VPN</a>

<a href="https://github.com/StreisandEffect/streisand/blob/master/README-chs.md">README-chs.md | 简体中文</a>

<p align="right"><b>高品质的VPN服务</b><br><i><a href="https://www.expressvpn.com/">ExpressVPN</a> &middot; <a href="https://vpnac.org">VPN.AC</a></i></p>

## 更多资源

#### <a href="https://github.com/WireGuard/WireGuard">WireGuard</a>

<a href="https://www.wireguard.com">www.wireguard.com</a>

#### <a href="https://github.com/jedisct1/dnscrypt-proxy">dnscrypt-proxy 2</a>

Windows —— <a href="https://simplednscrypt.org">Simple DNSCrypt</a>

#### <a href="https://github.com/greatfire">Greatfire</a>

<a href="https://torchina.gitlab.io/get/greatfire.html">https://torchina.gitlab.io/get/greatfire.html</a>

#### <a href="https://github.com/HelloZeroNet">ZeroNet</a> —— 需要MEEK代理

<a href="https://torchina.gitlab.io/get/zeronet.html">https://torchina.gitlab.io/get/zeronet.html</a>

#### Tails | 操作系统 —— 目前没有MEEK可用

<a href="https://torchina.gitlab.io/get/tails.html">https://torchina.gitlab.io/get/tails.html</a>

<b>政治聊天室 —— 没有自我审查</b>

[![Gitter](https://badges.gitter.im/chinapolitics/community.svg)](https://gitter.im/chinapolitics/community) | 
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

## 备用

<a href="https://raw.githubusercontent.com/mjstest/orgb1/0ea50a85a0a0f4253497498ec2d4a081/torbrowser-install-win64-8.0.8_zh-CN.exe">torbrowser-install-win64-8.0.8_zh-CN.exe</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb2/1fafade2a2cb44fb9918705d5a1cd352/browser.zip">browser.zip</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb1/5c98ddb799c47f073a0e3ad8e693f7e1/Shadowsocks-4.1.6.zip">Shadowsocks-4.1.6.zip</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb1/d3b1dbaf00469858df009a2f7f6a4f10/shadowsocks--universal-4.7.4.apk">shadowsocks--universal-4.7.4.apk</a> —— <a href="https://github.com/shadowsocks/openwrt-shadowsocks/releases">openwrt-shadowsocks</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb1/24e26ba7d534acf2e5f57ea42d030b30/PsiphonAndroid.apk">PsiphonAndroid.apk</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb1/9d3d7e1217ac56467fe3c921fdc46289/psiphon3.exe">psiphon3.exe</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb1/7d2320c9b2ca6716a8fbe765b524df19/Outline.ipa">Outline.ipa</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb1/0c18f6ae13e9e1b19dc59cfb67230256/Outline-Client.exe">Outline-Client.exe</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb2/24cd07219c3f3359a7d6d848d53b84cc/android-v1.2.10.apk">android-v1.2.10.apk</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb2/0353128dc41d2c0ae441cf019c8e0c4a/shadowsocks--universal-4.7.4.apk">shadowsocks--universal-4.7.4.apk</a> —— <a href="https://raw.githubusercontent.com/mjstest/orgb2/1274e9f2725c3b82826b89475801c09a/SimpleDNSCrypt64.msi">SimpleDNSCrypt64.msi</a>
