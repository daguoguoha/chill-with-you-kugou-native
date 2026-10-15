# 开源项目与第三方声明

| 项目 | 用途 | 许可证 |
|---|---|---|
| [KuGouMusicApi](https://github.com/MakcRe/KuGouMusicApi/tree/ba3645f2c89e6b9d4fec82ff783c15287e4c5f43) | 参考其请求签名、二维码、歌单及播放地址协议，以 C# 重新实现所需部分；不需要部署 Node 服务 | MIT，Copyright (c) 2023 MakcRe，见 licenses/KuGouMusicApi-LICENSE.txt |
| [Chill With You QQ 原生适配](https://github.com/daguoguoha/chill-with-you-qqmusic-native) / [网易云适配](https://github.com/daguoguoha/chill-with-you-netease-native) | 原生播放器接入、面板、安装器和音频解码基础代码 | GPL-3.0-or-later，根目录 LICENSE |
| [ChillPatcher](https://github.com/BeyondtheApex/ChillPatcher) | 原生音乐接口的研究来源 | GPL-3.0-or-later，licenses/ChillPatcher-LICENSE.txt |
| [BepInEx](https://github.com/BepInEx/BepInEx) | 5.4.23.5 Windows x64 加载框架，由安装器从官方 GitHub 下载 | MIT，licenses/BepInEx-LICENSE.txt |
| [HarmonyX](https://github.com/BepInEx/HarmonyX) | BepInEx 提供的运行时补丁 API | MIT，licenses/HarmonyX-LICENSE.txt |
| [NAudio](https://github.com/naudio/NAudio/tree/v2.2.1) | NAudio.Core / NAudio.Wasapi 2.2.1，从官方 NuGet 下载，通过 Windows Media Foundation 解码 | MIT，licenses/NAudio-LICENSE.txt |

游戏、Unity、TextMeshPro、UniTask、R3、ObservableCollections、Newtonsoft.Json 和系统程序集只从用户本地引用，不随包提供。此版没有使用 QQ Go 桥接、Go 运行时、Zig 或 QRCoder。完整适配源码和构建脚本随安装包提供，重新分发请保留版权与许可。
