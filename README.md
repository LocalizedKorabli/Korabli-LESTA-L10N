# Korabli-LESTA-L10N（战舰世界LESTA服非官方本地化）

## 背景

自2022年9月20日起，战舰世界独联体区玩家开始转移，一部分选择并入Wargaming直营欧服，另一部分则被分流到Lesta Games管理的新俄服（LESTA服）。

由于LESTA服主要面向俄罗斯和白俄罗斯玩家，其战舰世界客户端仅保留了俄语本地化文件。想在LESTA服游玩的非俄语玩家一般会用从直营服提取的本地化文件来覆盖俄语文件。这在最初是可行的，但随着时间流逝，LESTA服正在引入一些在Wargaming直营服未曾出现的内容，其文本显然不会被直营服的本地化文件所覆盖，从而不能正常显示，影响游玩体验。

于是，本项目应运而生。

## 如何使用

1. 在本仓库[Releases](https://github.com/Nova-Committee/Korabli-LESTA-L10N/releases)中，寻找“客户端版本号”数值最大、“发布时间”最晚的发布版本。这些发布版本的命名格式是“客户端版本号-发布时间”，如“7703463-20231007.1953”。
2. 下载该发布版本下的global.mo文件。

### 自动安装

3. 下载本仓库提供的[汉化安装器](https://github.com/Nova-Committee/Korabli-LESTA-L10N/releases/download/L10nInstaller-v2023.10.12.1910/L10nInstaller-v2023.10.12.1910.exe)，放入战舰世界安装目录后运行，按程序指示操作。
4. 启动游戏。

### 手动安装
3. 打开战舰世界安装目录下的bin文件夹，找到该文件夹下以数字命名且数值最大的一个或两个（若存在）文件夹：
4. 
- 方法一*：将这些文件夹下的res\locale_config.xml复制到res_mods\locale_config.xml，将复制后的文件中的“fonts="RU"”改成“fonts="CN"”；
- 方法二：分别打开这些文件夹下的res\locale_config.xml，将文件中的“fonts="RU"”改成“fonts="CN"”。
5. 若您不方便操作第4步，可以下载本仓库提供的[快捷程序](https://github.com/Nova-Committee/Korabli-LESTA-L10N/releases/download/modify_locale_config/modify_locale_cfg.exe)到第3步的数字文件夹下的res文件夹，运行即可完成操作（若使用方法一，再将软件运行后的res\locale_config.xml复制到res_mods\locale_config.xml）。
6.
- 方法一*：分别打开这些文件夹下的res_mods\texts\ru\LC_MESSAGES文件夹（若无则按名称自行创建），将第2步下载的global.mo文件放入；
- 方法二：分别打开这些文件夹下的res\texts\ru\LC_MESSAGES文件夹，将其中的global.mo文件备份后，用第2步下载的新global.mo文件覆盖。
7. 启动游戏。

*：推荐，非版本更新时不会被重置

## 常见问题

Q：兵工厂、造船厂没有被翻译？

A：这些页面实际上是由内置网页浏览器显示的，无法通过本地化文件翻译。

Q：游戏目录下的最新客户端版本号A和Releases中的最新客户端版本号B不一致？

A：
- A > B：本仓库本地化文件仍未更新，请耐心等待，或在确保原文件已备份的情况下尝试用仓库内最新的文件覆盖；
- A < B：在游戏强制更新前，Lesta会提前几天放出预更新，此时已能提取新版本的本地化文件进行翻译。若您未进行预更新，bin文件夹中则不会出现以未来版本号命名的文件夹。这也是“如何使用”第3步要求同时对两个文件夹操作的原因。

Q：游戏内不显示文字或只显示一些空心方块？又变回俄语了？

A：请检查你的所有步骤是否执行完毕。另外，每次客户端更新（包括小型更新）都有可能重置global.mo和locale_config.xml，你可能需要重新执行“如何使用”第3~6步或考虑在第4&6步使用方法一。
