# OpenWrt luci feed

[![Translation status](https://hosted.weblate.org/widgets/openwrt/-/svg-badge.svg)](https://hosted.weblate.org/engage/openwrt/?utm_source=widget)

## Modify Content
The prompt box after saving the application will disappear soon.

## 修改内容
保存应用程序后的提示框将很快消失。

## Description

This is the OpenWrt "luci"-feed containing LuCI - OpenWrt Configuration Interface.

## Usage

This feed is enabled by default. Your feeds.conf.default (or feeds.conf) should contain a line like:
```
src-git luci https://github.com/Flowers-in-thorns/luci.git;my-19.07
```

To install all its package definitions, run:
```
./scripts/feeds update luci
./scripts/feeds install -a -p luci
```

## API Reference

You can browse the generated API documentation [directly on Github](http://htmlpreview.github.io/?http://raw.githubusercontent.com/openwrt/luci/master/documentation/api/index.html).

## Development

Documentation for developing and extending LuCI can be found [in the Wiki](https://github.com/openwrt/luci/wiki)

## License

See [LICENSE](LICENSE) file.
 
## Package Guidelines

See [CONTRIBUTING.md](CONTRIBUTING.md) file.

## Translation status

[![Translation status](https://hosted.weblate.org/widgets/openwrt/-/multi-auto.svg)](https://hosted.weblate.org/engage/openwrt/?utm_source=widget)
