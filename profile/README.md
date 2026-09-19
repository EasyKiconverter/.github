# EasyKiConverter

**Open-source EDA conversion tools and infrastructure for electronic engineers.**

**面向电子工程师的开源 EDA 转换工具与基础设施。**

EasyKiconverter is the GitHub organization behind EasyKiConverter and its related open-source projects. We build tools that help engineers obtain, convert, validate, and integrate electronic component library data across EDA workflows.

EasyKiconverter 是围绕 EasyKiConverter 转换器及其衍生开源项目建立的 GitHub 组织，致力于为电子工程师提供元件数据获取、格式转换、验证和 EDA 工作流集成工具。

## Current Project · 当前项目

* [EasyKiConverter](https://github.com/EasyKiconverter/EasyKiConverter) — Qt 6 / C++17 desktop and CLI converter for LCSC and EasyEDA component data.

  Qt 6 / C++17 桌面与 CLI 转换器，用于处理 LCSC 和 EasyEDA 元件数据。
* [Documentation · 项目文档](https://easykiconverter.github.io/EasyKiConverter/)
* [Releases · 版本发布](https://github.com/EasyKiconverter/EasyKiConverter/releases)
* [Discussions · 社区讨论](https://github.com/EasyKiconverter/EasyKiConverter/discussions)
* [Contributing · 参与贡献](https://github.com/EasyKiconverter/EasyKiConverter/blob/master/docs/developer/CONTRIBUTING_en.md)

## Organization Direction · 组织发展方向

The organization may host complementary projects around the converter, including:

组织未来可能围绕转换器创建和维护以下配套项目：

* An official project website and documentation portal

  官方项目网站和文档门户
* Reusable conversion libraries and SDKs for application and automation integrations

  用于应用集成和自动化流程的可复用转换库与 SDK
* Format test suites, reference fixtures, and validation tools

  格式测试集、参考数据和验证工具
* Supporting utilities for packaging, data processing, and EDA workflows

  用于打包、数据处理和 EDA 工作流的辅助工具

These projects will be announced separately when they are created and ready for use. Planned projects should not be interpreted as currently available products.

这些项目将在实际创建并具备使用条件后分别公布。规划中的项目不代表当前已经存在或可用的产品。

## Capability Boundary · 能力边界

The latest stable EasyKiConverter release provides KiCad library export.

当前最新稳定版 EasyKiConverter 提供 KiCad 库导出功能。

The `master` branch is the development line for the shared intermediate representation and Altium Designer library export. Check the corresponding Release notes before relying on development-branch capabilities in a stable package.

`master` 分支用于开发统一中间表示和 Altium Designer 库导出能力。使用稳定安装包时，请以对应 Release 说明为准，不要将开发分支能力视为稳定版承诺。

## Platforms and License · 平台与许可证

Release packages are provided for supported architectures on **Windows · Linux · macOS**.

项目为 **Windows · Linux · macOS** 的受支持架构提供发布包。

EasyKiConverter is licensed under the [GNU General Public License v3.0](https://github.com/EasyKiconverter/EasyKiConverter/blob/master/LICENSE).

EasyKiConverter 使用 [GNU 通用公共许可证第三版](https://github.com/EasyKiconverter/EasyKiConverter/blob/master/LICENSE) 授权。