[release-img]: https://img.shields.io/github/release/docer-savior/search-everywhere-api-idea-plugin.svg
[latest-release]: https://github.com/docer-savior/search-everywhere-api-idea-plugin/releases/latest
[plugin-img]: https://img.shields.io/badge/plugin-19251-orange.svg
[plugin]: https://plugins.jetbrains.com/plugin/19251
[jet-img]: https://img.shields.io/badge/plugin-Install%20Plugin-4597ff.svg
[jet]: http://localhost:63342/api/installPlugin?action=install&pluginId=gudqs7.github.io.search.everywhere.api

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT_CN.md)
[![license](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![GitHub release][release-img]][latest-release] [![Jetbrains Plugins][plugin-img]][plugin]
[![Version](http://phpstorm.espend.de/badge/19251/version)][plugin]  
[![Downloads](http://phpstorm.espend.de/badge/19251/downloads)][plugin]
[![Install Plugins][jet-img]][jet]

---
[English 🇺🇸](./README_EN.md)

# Search Everywhere Api 是做什么的？

- 是一个 IDEA 插件，仅支持 Java 。
- 通过 Search Everywhere 搜索 Api。

# 我该如何开始？

## 1.安装插件
### zip 包安装
从最新的 [Release][latest-release] 页下载 zip 包，然后打开 IDEA，进入 Settings --> Plugins --> 小齿轮 --> Install Plugin from Disk  
![zip](parts/imgs/install-plugin-from-disk.png)

### Marketplace 安装
打开 IDEA，进入 Settings --> Plugins，选中 Marketplace，输入 Search Everywhere Api 点击 Install  
![Marketplace](parts/imgs/install-from-marketplace.png)

## 2.打开一个 Spring MVC 或 Dubbo 项目
建议直接打开我专门准备的示例项目：[docer-savior-plugin-usage-examples](https://github.com/docer-savior/docer-savior-plugin-usage-examples)

```shell
git clone https://github.com/docer-savior/docer-savior-plugin-usage-examples
```

## 3.通过 Search Everywhere 搜索 Api

双击 `Shift` 进入 `Search Everywhere` 后切换到 Api，或使用快捷键 `Ctrl + \ ` 或 `Ctrl + Alt + N` 进入如下图界面。    
此时您可通过 url 或接口描述来搜索并跳转到该接口。


![img.png](parts/imgs/search-everywhere-api.png)  
不输入任何数据时，展示所有 Api；另外可以根据方法类型筛选。  
![img.png](parts/imgs/search-everywhere-api-show-all.png)  
在 All 下也可以搜索  
![img.png](parts/imgs/search-everywhere-api-all.png)


# 如果需要，我可以从哪里获得更多帮助？

## 通过提交 Issue 来获取帮助
[点击访问 Github Issue](https://github.com/docer-savior/search-everywhere-api-idea-plugin/issues)
> 欢迎大家提问，欢迎大家一起完善它！

**另外，我接入了 IDEA 的错误处理组件，因此当发现插件报错提示时，按照 IDEA 提示，可查看错误信息，并一键上报给我（即自动生成一个 Issue）**

## 通过查看 Wiki 来获取更多说明

[点击访问 Wiki](https://github.com/docer-savior/search-everywhere-api-idea-plugin/wiki/%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B)

## 贡献指南
[贡献指南](CONTRIBUTING_CN.md)

# 致谢名单

- [Github RESTKit](https://github.com/newhoo/RESTKit)