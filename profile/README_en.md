# EasyKiConverter

English | [简体中文](README.md)

**Open-source EDA conversion tools and infrastructure for electronic engineers.**

EasyKiconverter is the GitHub organization behind EasyKiConverter and its related open-source projects. We build tools that help engineers obtain, convert, validate, and integrate electronic component library data across EDA workflows.

## Current Project

* [EasyKiConverter](https://github.com/EasyKiconverter/EasyKiConverter) — Qt 6 / C++17 desktop and CLI converter for LCSC and EasyEDA component data
* [Documentation](https://easykiconverter.github.io/EasyKiConverter/)
* [Releases](https://github.com/EasyKiconverter/EasyKiConverter/releases)
* [Discussions](https://github.com/EasyKiconverter/EasyKiConverter/discussions)
* [Contributing](https://github.com/EasyKiconverter/EasyKiConverter/blob/master/docs/developer/CONTRIBUTING_en.md)

## Organization Direction

The organization may host complementary projects around the converter, including:

* An official project website and documentation portal
* Reusable conversion libraries and SDKs for application and automation integrations
* Format test suites, reference fixtures, and validation tools
* Supporting utilities for packaging, data processing, and EDA workflows

These projects will be announced separately when they are created and ready for use. Planned projects should not be interpreted as currently available products.

## Capability Boundary

The latest stable EasyKiConverter release provides KiCad library export.

The `master` branch is the development line for the shared intermediate representation and Altium Designer library export. Check the corresponding Release notes before relying on development-branch capabilities in a stable package.

## Platforms and License

Release packages are provided for supported architectures on **Windows · Linux · macOS**.

EasyKiConverter is licensed under the GPL3.0(https://github.com/EasyKiconverter/EasyKiConverter/blob/master/LICENSE).