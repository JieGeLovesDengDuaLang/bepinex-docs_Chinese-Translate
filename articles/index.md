# BepInEx 教程

欢迎来到 BepInEx 文档！

## BepInEx 是什么

BepInEx (Bepis Injector Extendable) 是一个针对基于 Unity 和 .NET 框架的游戏的插件框架。

BepInEx 的目标：

* 对使用者们友好，易于安装与使用；
* 为模组制作提供必要的工具；
* 体积小巧，尽可能支持多的 Unity 游戏。

虽然 BepInEx 主要针对的是运行在 Windows 操作系统上的游戏，但 BepInEx 也能够在 Linux、macOS 以及其它支持 Mono 或仿 Windows 的操作系统上运行。

## BepInEx 不是什么

Currently, BepInEx does not aim to be the solution for modding all games with .NET support on all platforms.
This limitation allows BepInEx to be small and simple to install while still working on as many games as possible.

BepInEx is also not an all-in-one tool that caters to every single user.
Instead, BepInEx provides only the necessary base to develop game-specific support.
BepInEx is made to be *extendable*: you can modify and add parts of BepInEx to make it work best for you.

## Getting started with BepInEx

To start with BepInEx, you should [download and install it](<xref:installation>).  
Next, you might want to [configure it and any of the plugins you install](<xref:configuration>).

> [!NOTE]  
> While BepInEx should work with default configuration on most Unity games, some games might require a specific entry point configuration.
> Refer to [troubleshooting information](<xref:troubleshooting>) for info on how to set up entry points in exceptional cases.

## Developing plugins

> [!IMPORTANT]
> BepInEx 6 documentation is in development. At the moment, most developer documentation refers to BepInEx 5.
> Always refer to the [API documentation](~/api/index.md) for up-to-date BepInEx API.

If you are a developer, you can check the [plugin creation walkthrough](<xref:plugin_dev_index>) to get acquainted with most of the API of BepInEx.
Additionally, you should check out [how to use Harmony to patch game methods](<xref:runtime_patching>).

For more exact documentation on each of BepInEx's feature, consult the [API documentation](~/api/index.md)

Finally, the advanced guides contain information on how to debug plugins with dnSpy and elaborate on technical details of BepInEx and Unity modding.
