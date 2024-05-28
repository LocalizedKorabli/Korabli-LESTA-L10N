<div align=center>

  <img  width="160" src="https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/assets/81358657/26415d14-c46e-4bdd-aa26-f7f0234911ce" alt="logo">

<h3>战舰世界莱服非官方本地化</h3>

![stars](https://img.shields.io/github/stars/LocalizedKorabli/Korabli-LESTA-L10N.svg)
[![release](https://img.shields.io/github/release/LocalizedKorabli/Korabli-LESTA-L10N.svg)](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/releases/latest)
![last-commit](https://img.shields.io/github/last-commit/LocalizedKorabli/Korabli-LESTA-L10N.svg)

</div>

## 如何使用

### 下载

#### 通过国内网盘

[蓝奏云](https://tapio.lanzouw.com/b01lit85i)（密码：256r）

1. 汉化安装器：选择“汉化安装器”文件夹，下载最新`exe`文件；
2. （汉化安装器已内置汉化包下载功能，按需下载）汉化包：根据游戏版本选择正确的文件夹，下载最新压缩包并解压出`global.mo`文件。

#### 通过 GitHub

1. 汉化安装器：[下载](https://github.com/LocalizedKorabli/L10nInstaller/releases/download/v2024.05.29.0049/L10nInstaller-v2024.05.29.0049.exe)；
2. 汉化包（汉化安装器已内置汉化包下载功能，按需下载）：在本仓库 [Releases](https://github.com/LocalizedKorabli/Korabli-LESTA-L10N/releases/latest) 中，下载该发布版本下的`global.mo`文件；

### 安装

1. 下载汉化安装器，放入战舰世界安装目录后运行，按程序指示操作；
2. 若汉化安装器内置下载失败，请手动下载汉化包并选择“使用本地文件”。

### \[可选\]使用“模组（汉化修改包）”

自`v2024.03.30.1528`版本开始，汉化安装器可以自动将放置于`l10n_installer/mods/`目录的`mo`文件应用到即将被安装的汉化包。

#### 下载模组

[蓝奏云](https://tapio.lanzn.com/b0nxzso2b) | [GitHub](https://github.com/LocalizedKorabli/L10nModifications)

#### 安装模组

1. 将相应模组的`mo`文件（从蓝奏云下载的模组需先解压）放入游戏目录下`l10n_installer`文件夹下的`mods`文件夹（这些文件夹会在第一次运行汉化安装器时被创建）；
2. 运行汉化安装器，在提示`是否将l10n_installer/mods/下的模组应用到汉化文件？`时输入Y后按回车键，等待安装器将汉化修改包应用到即将被安装的汉化包。

## Q&A

- Q：为什么兵工厂、造船厂没有被翻译？

  A：这些页面实际上是由内置网页浏览器显示的，无法通过本地化文件翻译。
  
- Q：为什么游戏内文本又变回俄语了？

  A：每次版本更新时都会更换`bin`目录下的数字文件夹，重新安装汉化包即可。
  
- Q：为什么一些本该意译的船名被音译了？

  A：部分意译船名可能存在敏感内容，会给想要直播莱服游玩的汉化用户带来不便。若您需要意译版本的船名，请考虑使用汉化修改包（使用方法见本文-如何使用-使用“模组（汉化修改包）”）。

## 贡献

[贡献指南](CONTRIBUTING.md)

## 关于

自 2022年 9月 20日起，战舰世界独联体区玩家开始转移，一部分选择并入 Wargaming 直营欧服，另一部分则被分流到 Lesta Games 管理的新俄服（LESTA 服）。

由于 LESTA 服主要面向俄罗斯和白俄罗斯玩家，其战舰世界客户端仅保留了俄语本地化文件。
想在 LESTA 服游玩的非俄语玩家一般会用从直营服提取的本地化文件来覆盖俄语文件。
这在最初是可行的，但随着时间流逝，LESTA 服正在引入一些在 Wargaming 直营服未曾出现的内容，
其文本显然不会被直营服的本地化文件所覆盖，从而不能正常显示，影响游玩体验。

于是，本项目应运而生。

## 相关链接

[Gitee](https://gitee.com/nova-committee/korabli-LESTA-L10N)

[Korabli Forum发布页](https://forum.korabli.su/topic/161848-133-%D0%BA%D0%B8%D1%82%D0%B0%D0%B9%D1%81%D0%BA%D0%B0%D1%8F-%D0%BB%D0%BE%D0%BA%D0%B0%D0%BB%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D1%8F%E4%B8%AD%E6%96%87%E6%9C%AC%E5%9C%B0%E5%8C%96/)

[Bilibili专栏](https://www.bilibili.com/opus/918285182086152224)

[Patreon](https://www.patreon.com/LocalizedKorabli)
