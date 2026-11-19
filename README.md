# TerraMoor

TerraMoor 在 ColorOS 17 的原生媒体胶囊中显示同步歌词。可调整原文和译文字号、对齐方式、前摄边缘渐隐、封面模糊和逐句动效。调整页提供日语、英语、韩语预览，支持备份和恢复配置。

## 预览

![原生胶囊动态预览](https://raw.githubusercontent.com/Luckyumimi/TerraMoor/main/docs/previews/capsule-preview.gif)

| 应用内预览 | 系统流体云 |
| --- | --- |
| ![应用内胶囊](https://raw.githubusercontent.com/Luckyumimi/TerraMoor/main/docs/previews/app-capsule.png) | ![系统媒体胶囊](https://raw.githubusercontent.com/Luckyumimi/TerraMoor/main/docs/previews/system-capsule.png) |

## 已支持的设备

- 机型 `PKX110`
- 固件 `PKX110_17.0.0.104(CN01)`
- SystemUI `17.99.02` 与 SystemUIPlugin `17.000.002`
- 支持现代模块 API 102 的 LSPosed

## 使用方法

1. 安装正式 APK，在 LSPosed 启用 TerraMoor，作用域勾选「系统界面」。重新启动 SystemUI 以加载模块。
2. 打开 TerraMoor，启用「流体云歌词」。播放器需要发布同步歌词。如果播放器不提供，可在 [ColorOS Live Lyrics Bridge](https://github.com/Andrea-lyz/ColorOS-Live-Lyrics-Bridge) 的商店选择对应 Provider。
3. 打开「调整」页，拖动滑块时可在应用预览和系统媒体胶囊中查看效果。停用时可在 TerraMoor 里关闭功能，或在 LSPosed 停用模块后重新启动 SystemUI。

Root 仅用于应用内的「重启系统界面」按钮，执行前会弹出确认。歌词和配置在本机处理。如果同时安装了本地调试包，请在 LSPosed 里停用调试包，再启用正式包。需要迁移设置时，可在旧包的「关于」页导出 JSON，在正式包里导入。

源码与反馈见 [Luckyumimi/TerraMoor](https://github.com/Luckyumimi/TerraMoor)，QQ 群 `1102727864`。

日语预览使用《ツクヨミステップ》的封面与简短歌词示例。
