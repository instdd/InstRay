# v2rayNG

A V2Ray client for Android, support [Xray core](https://github.com/XTLS/Xray-core) and [v2fly core](https://github.com/v2fly/v2ray-core)

[![API](https://img.shields.io/badge/API-21%2B-yellow.svg?style=flat)](https://developer.android.com/about/versions/lollipop)
[![Kotlin Version](https://img.shields.io/badge/Kotlin-2.1.21-blue.svg)](https://kotlinlang.org)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/2dust/v2rayNG)](https://github.com/2dust/v2rayNG/commits/master)
[![CodeFactor](https://www.codefactor.io/repository/github/2dust/v2rayng/badge)](https://www.codefactor.io/repository/github/2dust/v2rayng)
[![GitHub Releases](https://img.shields.io/github/downloads/2dust/v2rayNG/latest/total?logo=github)](https://github.com/2dust/v2rayNG/releases)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-brightgreen.svg)](https://t.me/v2rayn)

### Telegram Channel
[InstVpn](https://t.me/instvpnofficial)

### Telegram Bot
[InstVpn](https://t.me/reels_vpn_bot)

### Usage

#### Geoip and Geosite
- geoip.dat and geosite.dat files are in `Android/data/com.instray.ang/files/assets` (path may differ on some Android device)
- download feature will get enhanced version in this [repo](https://github.com/Loyalsoldier/v2ray-rules-dat) (Note it need a working proxy)
- latest official [domain list](https://github.com/Loyalsoldier/v2ray-rules-dat) and [ip list](https://github.com/Loyalsoldier/geoip) can be imported manually
- possible to use third party dat file in the same folder, like [h2y](https://guide.v2fly.org/routing/sitedata.html#%E5%A4%96%E7%BD%AE%E7%9A%84%E5%9F%9F%E5%90%8D%E6%96%87%E4%BB%B6)

### More in our [wiki](https://github.com/2dust/v2rayNG/wiki)

### Development guide

Android project under V2rayNG folder can be compiled directly in Android Studio, or using Gradle wrapper. But the v2ray core inside the aar is (probably) outdated.  
The aar can be compiled from the Golang project [AndroidLibV2rayLite](https://github.com/2dust/AndroidLibV2rayLite) or [AndroidLibXrayLite](https://github.com/2dust/AndroidLibXrayLite).
For a quick start, read guide for [Go Mobile](https://github.com/golang/go/wiki/Mobile) and [Makefiles for Go Developers](https://tutorialedge.net/golang/makefiles-for-go-developers/)

v2rayNG can run on Android Emulators. For WSA, VPN permission need to be granted via
`appops set [package name] ACTIVATE_VPN allow`
