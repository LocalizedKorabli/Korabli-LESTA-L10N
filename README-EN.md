<div align=center>

  <img  width="160" src="https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/assets/81358657/26415d14-c46e-4bdd-aa26-f7f0234911ce" alt="logo">

<h3>Unofficial Localization for Mir Korabli</h3>

[![stars](https://img.shields.io/github/stars/LocalizedKorabli/Korabli-LESTA-L10N.svg?style=for-the-badge)](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/stargazers)
[![release](https://img.shields.io/github/release/LocalizedKorabli/Korabli-LESTA-L10N.svg?style=for-the-badge)](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/releases/latest)
[![last-commit](https://img.shields.io/github/last-commit/LocalizedKorabli/Korabli-LESTA-L10N.svg?style=for-the-badge)](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/commit)

[![发布群](https://img.shields.io/badge/QQ-Publish-red?style=for-the-badge)](https://qm.qq.com/q/oLZZH47TRA)
[![闲聊群](https://img.shields.io/badge/QQ-Chat-blue?style=for-the-badge)](https://qm.qq.com/q/n3gtv0yfwQ)
[![Discord](https://img.shields.io/discord/1275430075369656381?style=for-the-badge)](https://discord.gg/3d9k2mkWy4)

</div>

[简体中文](/README.md) | **English**

Looking for English Localization? Check [Korabli-LESTA-I18N](https://github.com/LocalizedKorabli/Korabli-LESTA-I18N)!

## Download & Installation

<details><summary style="font-size: 20px;">Showcase Video (in Chinese)</summary>

[![](https://github.com/user-attachments/assets/d5918619-f147-4f0f-8871-c2e7f0be6976)](https://player.bilibili.com/player.html?aid=112944050341775&bvid=BV1rDYReAEws&cid=25777407882&page=1)

</details>

<details><summary style="font-size: 20px;">Introduction Video (in Chinese)</summary>

[![](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/assets/81358657/d8d44d1f-f448-4feb-ab07-7ab2ccbca54e)](https://player.bilibili.com/player.html?aid=1755946809&bvid=BV1c4421D7Gh&cid=1596825150&page=1)

</details>

### Download

#### Via Lanzou Drive

1. L10n Installer ([GUI Implementation](https://tapio.lanzn.com/b0nybehgb) | [CLI (old)](https://tapio.lanzn.com/b0nybx87c) ): Download the latest executable file;
2. (Downloading feature is built into the Installer) [L10n Package](https://tapio.lanzn.com/b01lit85i): Choose the correct directory refer to the client version，and extract the `global.mo` file from the downloaded archive.

#### Via GitHub

1. L10n Installer: [GUI Implementation](https://github.com/LocalizedKorabli/L10nInstallerGUI/releases/latest) | [CLI (old)](https://github.com/LocalizedKorabli/L10nInstaller/releases/latest);
2. (Downloading feature is built into the Installer) L10n Package: Extract the `global.mo` file from the downloaded archive in the [latest release](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/releases/latest).

### Installation

1. Place the downloaded executable into Mir Korabli's installation directory, run and operate the program under its instruction;
2. In case the built-in download feature goes wrong, please manually download the l10n package and use `Local File`.

<details><summary style="font-size: 20px;">Optional</summary>

#### Mods (Modifications)

The installer can automatically apply mods (usually `.po` or `.mo`) in the `l10n_installer/mods/`directory to the l10n package to be installed.

#### Download Mods

[Lanzou Drive](https://tapio.lanzn.com/b0nxzso2b) | [GitHub](https://github.com/LocalizedKorabli/L10nModifications)

#### Apply Mods

- Place the `mo` files (extract from, if downloaded via Lanzou Drive, the downloaded archives) to the `<GamePath>/l10n_installer/mods` directory, which is created once you run the installer;
- Run the installer;
- (GUI Implementation) Select `Apply Mods`;
- (CLI) Press `Y` and enter when it notifies `Do you want to apply the mods in l10n_installer/mods/ to the l10n package?`

</details>

## Q&A

- Q: Armory and dockyard unlocalized?

  A: Those are website pages displayed by the game's built-in browser and are not able to be localized via MO localization.
  
- Q: After a certain startup, the game shows up in Russian again?

  A: The build number folder in the `bin` directory is replaced with each version update, just reinstall the package.

## Contributing

[Contributing Guide](CONTRIBUTING.md)

## Background

As of September 20, 2022, World of Warships CIS Zone players have begun to transfer, with some choosing to merge into Wargaming's European server and others being shunted to the new Russian server (Lesta server) managed by Lesta Games.

As the Lesta server is primarily for Russian and Belarusian players, its World of Warships client retains only the Russian localization files.
Non-Russian-speaking players who wanted to play on the Lesta servers would generally overwrite the Russian language files with localization files extracted from the Wargaming client.
This worked initially, but as versions change, the Lesta server is introducing content that was not present on the Wargaming server.
Its text will obviously not be overwritten by the Wargaming's, and thus will not display properly, affecting the experience.

Thus, this project was born.

## Portal

LocalizedKorabli is making localizations for multiple languages and server types.
You can easily access the corresponding project repositories by clicking on the links in the table below.

| Language\Server Type | Live Server | Public Test Server |
|:--------------------:|:-----------:|:------------------:|
| L10N-简体中文 | **This Repository** | [Repository Link](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N-PublicTest) |
| I18N-English | [Repository Link](https://github.com/LocalizedKorabli/Korabli-LESTA-I18N) | [Repository Link](https://github.com/LocalizedKorabli/Korabli-LESTA-I18N-PublicTest) |


## Relative links

[Gitee](https://gitee.com/nova-committee/korabli-LESTA-L10N)

[Korabli Forum Release Page](https://forum.korabli.su/topic/161848-/)

[Bilibili Video Tutorial](https://www.bilibili.com/video/BV1c4421D7Gh)

[Bilibili Article](https://www.bilibili.com/opus/918285182086152224)

[Patreon](https://www.patreon.com/LocalizedKorabli)

## Similar projects

### [Lavandel's modification based on this project](https://github.com/EGIST-Lavandel/RU2CNKorabliModificate)

A third-party modification based on the 8275422-20240410.2319 version of this project, updating actively after forking.

Style: Creative and amusing.

### [REPAD Localization](https://github.com/DDFantasyV/Korabli_localization_chs)

Another localization project, which started almost at the same time as this project, focuses on smooth, discreet translations of the added text.
