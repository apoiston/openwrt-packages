# OpenWrt Packages

---

### Package Repositories

- [infinityapps](https://infinityapps.pages.dev/)

- [infinitykmods](https://infinitykmods.pages.dev/)

- [infinitypackages](https://infinitypackages.pages.dev/)

### Firmware Download

- [Releases](https://github.com/apoiston/openwrt-builder/releases)

### Usage

```shell
# Add key
wget -O /etc/apk/keys/infinityapps.pem https://infinityapps.pages.dev/public-key.pem
```

```shell
# Add feed
echo "https://infinityapps.pages.dev/snapshots/x86_64/apps/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

```shell
# Install packages
apk update && apk add luci-i18n-nikki-zh-cn
```

### Credits

- [Joseph Mory](http://github.com/morytyann)

- [OpenWrt](https://github.com/openwrt/openwrt)

- [OpenWrt LuCI](https://github.com/openwrt/luci)

- [OpenWrt Packages](https://github.com/openwrt/packages)

- [GitHub](https://github.com)

- [GitHub Actions](https://github.com/features/actions)

- [MetaCubeX/mihomo](https://github.com/MetaCubeX/mihomo)

- [timsaya/bandix](https://github.com/timsaya/luci-app-bandix)
