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
# add key
wget -O /etc/apk/keys/infinity.pem https://infinityapps.pages.dev/public-key.pem
```

```shell
# add feed
echo "https://infinityapps.pages.dev/snapshots/x86_64/apps/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

```shell
# install packages
apk add --no-cache luci-i18n-nikki-zh-cn
```

```shell
# upgrade packages
apk add -U nikki luci-app-nikki luci-i18n-nikki-zh-cn
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
