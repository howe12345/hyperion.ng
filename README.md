![Hyperion](doc/logo_dark.png#gh-dark-mode-only)
![Hyperion](doc/logo_light.png#gh-light-mode-only)

[![Latest-Release](https://img.shields.io/github/v/release/hyperion-project/hyperion.ng?include_prereleases)](https://github.com/hyperion-project/hyperion.ng/releases)
[![GitHub Actions](https://github.com/hyperion-project/hyperion.ng/workflows/Hyperion%20CI%20Build/badge.svg?branch=master)](https://github.com/hyperion-project/hyperion.ng/actions)
[![LGTM](https://img.shields.io/lgtm/alerts/g/hyperion-project/hyperion.ng.svg)](https://lgtm.com/projects/g/hyperion-project/hyperion.ng/alerts/)
[![Forum](https://img.shields.io/website/https/hyperion-project.org.svg?label=Forum&down_color=red&down_message=offline&up_color=green&up_message=online)](https://www.hyperion-project.org)
[![Documentation](https://img.shields.io/website?down_message=offline&label=Documentation%20%20&up_message=online&url=https%3A%2F%2Fdocs.hyperion-project.org)](https://docs.hyperion-project.org)
[![Discord](https://img.shields.io/discord/785578322167463937?label=Discord)](https://discord.gg/khkR8Vx3ff)
![made-with-love](https://img.shields.io/badge/Made%20with-&#9829;-ff0000.svg)

## About Hyperion

[Hyperion](https://github.com/hyperion-project/hyperion.ng) is an opensource [Bias or Ambient Lighting](https://en.wikipedia.org/wiki/Bias_lighting) implementation which you might know from TV manufacturers. It supports many LED devices and video grabbers.

![Screenshot](doc/screenshot.png)

### Features:

* Low CPU load makes it perfect for SoCs like Raspberry Pi
* Json interface which allows easy integration into scripts
* A command line utility for testing and integration in automated environment
* Priority channels are not coupled to a specific led data provider which means that a provider can post led data and leave without the need to maintain a connection to Hyperion. This is ideal for a remote application (like our [Android app](https://play.google.com/store/apps/details?id=nl.hyperion.hyperionpro)).
* Black border detector and processor
* A scriptable (Python) effect engine with 39 build-in effects for your inspiration
* A multi language web interface to configure and remote control hyperion

If you need further support please open a topic at the forum!<br>
[![Forum](https://img.shields.io/website/https/hyperion-project.org.svg?label=Forum&down_color=red&down_message=offline&up_color=green&up_message=online)](https://www.hyperion-project.org)

## Contributing

Contributions are welcome! Feel free to join us! We are looking always for people who wants to participate.<br>
[![Contributors](https://img.shields.io/github/contributors/hyperion-project/hyperion.ng.svg?label=Contributors)](https://github.com/hyperion-project/hyperion.ng/graphs/contributors)

For an example, you can participate in the translation.<br>
[![Join Translation](https://img.shields.io/badge/POEditor-translate-green.svg)](https://poeditor.com/join/project/Y4F6vHRFjA)

## Supported Platforms

Find here more details on [supported platforms and configuration sets](doc/development/SupportedPlatforms.md)

## Documentation
Covers these topics:
- [Installation](https://docs.hyperion-project.org/en/user/Installation.html)
- [Configuration](https://docs.hyperion-project.org/en/user/Configuration.html)
- [Effect development](https://docs.hyperion-project.org/en/effects/#effect-files)
- [JSON API](https://docs.hyperion-project.org/en/json/)

[![Visit Documentation](https://img.shields.io/website?down_message=offline&label=Documentation%20%20&up_message=online&url=https%3A%2F%2Fdocs.hyperion-project.org)](https://docs.hyperion-project.org)

## Changelog
Released and unreleased changes at [CHANGELOG.md](CHANGELOG.md)

## Building
See [CompileHowto](doc/development/CompileHowto.md).

## Installation
See [Documentation](#documentation) or at [Installation.md](Installation.md).

## Download
Releases available from the [Hyperion release page](https://github.com/hyperion-project/hyperion.ng/releases)

## License
The source is released under MIT-License (see https://opensource.org/licenses/MIT).<br>
[![GitHub license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://raw.githubusercontent.com/hyperion-project/hyperion.ng/master/LICENSE)

