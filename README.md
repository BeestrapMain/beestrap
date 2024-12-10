> [!CAUTION]
> The only official places to download Beestrap are this GitHub repository. Any other websites offering downloads or claiming to be us are not controlled by us.

<p align="center">
    <img src="https://github.com/real-bery/beestrap/raw/main/Beestrap.png#gh-dark-mode-only" width="420">
    <img src="https://github.com/real-bery/beestrap/raw/main/Beestrap.png#gh-light-mode-only" width="420">
</p>

<div align="center">

[![License][shield-repo-license]][repo-license]
[![GitHub Workflow Status][shield-repo-workflow]][repo-actions]
[![Crowdin][shield-crowdin-status]][crowdin-project]
[![Downloads][shield-repo-releases]][repo-releases]
[![Version][shield-repo-latest]][repo-latest]
[![Discord][shield-discord-server]][discord-invite]

</div>

----

Beestrap is a third-party replacement for the standard Roblox bootstrapper, providing additional useful features and improvements.

## Features

- Hassle-free Discord Rich Presence to let your friends know what you're playing at a glance
- Simple support for modding of content files for customizability (death sound, mouse cursor, etc)
- See where your server is geographically located (courtesy of [ipinfo.io](https://ipinfo.io))
- Ability to configure graphics fidelity and UI experience
- Multi instance support

## Installing
Download the [latest release of Beestrap](https://github.com/real-bery/beestrap/releases/latest), and run it. Configure your preferences if needed, and install. That's about it!

Alternatively, you can install Beestrap via [Winget](https://winstall.app/apps/bery.Beestrap) by running this in a Command Prompt window:
```
> winget install beestrap
```

You will also need the [.NET 6 Desktop Runtime](https://aka.ms/dotnet-core-applaunch?missing_runtime=true&arch=x64&rid=win11-x64&apphost_version=6.0.16&gui=true). If you don't already have it installed, you'll be prompted to install it anyway. Be sure to install Beestrap after you've installed this.

Beestrap is not malicious, it will show the Windows Smartscreen when you run Beestrap for the first time. This happens because of: Unknown program, To dismiss it, click on 'More info' and then 'Run anyway'.

Once installed, Beestrap is added to your Start Menu, where you can access the menu and reconfigure your preferences if needed.

## Code

Beestrap uses the [WPF UI](https://github.com/lepoco/wpfui) library for the user interface design. We currently use and maintain our own fork of WPF UI at [real-bery/wpfui](https://github.com/real-bery/wpfui).


[shield-repo-license]:  https://img.shields.io/github/license/real-bery/beestrap
[shield-repo-workflow]: https://img.shields.io/github/actions/workflow/status/real-bery/beestrap/ci-release.yml?branch=main&label=builds
[shield-repo-releases]: https://img.shields.io/github/downloads/real-bery/beestrap/latest/total?color=f6ff00
[shield-repo-latest]:   https://img.shields.io/github/v/release/real-bery/beestrap?color=f6ff00

[shield-crowdin-status]: https://badges.crowdin.net/bloxstrap/localized.svg
[shield-discord-server]: https://img.shields.io/discord/1316144065527545946?logo=discord&logoColor=white&label=discord&color=f6ff00

[repo-license]:  https://github.com/real-bery/beestrap/blob/main/LICENSE
[repo-actions]:  https://github.com/real-bery/beestrap/actions
[repo-releases]: https://github.com/real-bery/beestrap/releases
[repo-latest]:   https://github.com/real-bery/beestrap/releases/latest

[crowdin-project]: https://crowdin.com/project/beestrap
[discord-invite]:  https://discord.gg/UB2mgfmT3X
