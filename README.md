# TerraMoor

TerraMoor 在 ColorOS 17 的原生媒体胶囊中显示同步歌词。可调整原文和译文字号、对齐方式、前摄边缘渐隐、封面模糊和逐句动效。调整页提供日语、英语、韩语预览，支持备份和恢复配置。

模块开源地址：

[https://github.com/Luckyumimi/TerraMoor](https://github.com/Luckyumimi/TerraMoor)


## 预览

![原生胶囊动态预览](https://raw.githubusercontent.com/Luckyumimi/TerraMoor/main/docs/previews/capsule-preview.gif)

| 应用内预览 | 系统流体云 |
| --- | --- |
| ![应用内胶囊](https://raw.githubusercontent.com/Luckyumimi/TerraMoor/main/docs/previews/app-capsule.png) | ![系统媒体胶囊](https://raw.githubusercontent.com/Luckyumimi/TerraMoor/main/docs/previews/system-capsule.png) |


## 使用方法

1. 安装模块，在 LSPosed 启用 TerraMoor，作用域勾选「系统界面」。重新启动 SystemUI 以加载模块。
2. 打开 TerraMoor，启用「流体云歌词」。播放器需要发布同步歌词。如果播放器不提供，可在 [ColorOS Live Lyrics Bridge](https://github.com/Andrea-lyz/ColorOS-Live-Lyrics-Bridge) 的商店选择对应 Provider。
3. 尽管如此，我们还是希望你对于所有播放器挂载 **通用播放器 Provider**。
4. 「调整」页面中，拖动滑块时可在应用预览和系统媒体胶囊中查看效果。一般都会在原生流体云实时生效，app内预览作为参考。

Root 仅用于应用内的「重启系统界面」按钮，执行前会弹出确认。歌词和配置在本机处理。

源码与反馈见 [Luckyumimi/TerraMoor](https://github.com/Luckyumimi/TerraMoor)，QQ 群 `1102727864`。
