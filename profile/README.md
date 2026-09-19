# EasyKiConverter

简体中文 | [English](README_en.md)

**面向电子工程师的开源 EDA 转换工具与基础设施。**

EasyKiconverter 是围绕 EasyKiConverter 转换器及其衍生开源项目建立的 GitHub 组织，致力于为电子工程师提供元件数据获取、格式转换、验证和 EDA 工作流集成工具。

## 当前项目

* [EasyKiConverter](https://github.com/EasyKiconverter/EasyKiConverter) — 基于 Qt 6 / C++17 的桌面与 CLI 转换器，用于处理 LCSC 和 EasyEDA 元件数据
* [项目文档](https://easykiconverter.github.io/EasyKiConverter/)
* [版本发布](https://github.com/EasyKiconverter/EasyKiConverter/releases)
* [社区讨论](https://github.com/EasyKiconverter/EasyKiConverter/discussions)
* [参与贡献](https://github.com/EasyKiconverter/EasyKiConverter/blob/master/docs/developer/CONTRIBUTING.md)

## 组织发展方向

组织未来可能围绕转换器创建和维护以下配套项目：

* 官方项目网站和文档门户
* 用于应用集成和自动化流程的可复用转换库与 SDK
* 格式测试集、参考数据和验证工具
* 用于打包、数据处理和 EDA 工作流的辅助工具

这些项目将在实际创建并具备使用条件后分别公布。规划中的项目不代表当前已经存在或可用的产品。

## 能力边界

当前最新稳定版 EasyKiConverter 提供 KiCad 库导出功能。

`master` 分支用于开发统一中间表示和 Altium Designer 库导出能力。使用稳定安装包时，请以对应 Release 说明为准，不要将开发分支能力视为稳定版承诺。

## 平台与许可证

项目为 **Windows · Linux · macOS** 的受支持架构提供发布包。

EasyKiConverter 使用 [GPL3.0](https://github.com/EasyKiconverter/EasyKiConverter/blob/master/LICENSE) 授权。