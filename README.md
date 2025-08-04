![Vibrant Visuals Optimization](/Main%20Pack/Sample%20image.png)
<div align=center>

# Vibrant Visuals Optimization

English / [简体中文](./README-CN.md)

</div>

[![CC0](https://img.shields.io/badge/License-CC0-blue.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Page](https://img.shields.io/badge/Github-Page-green.svg)](https://docs.miaowcham.top/Project/Vibrant-Visuals-Optimization-Docs/)
[![Repository](https://img.shields.io/badge/Github-Repository-purple.svg)](https://github.com/MiaowCham/Vibrant-Visuals-Optimization)
[![Actions](https://img.shields.io/github/actions/workflow/status/MiaowCham/Vibrant-Visuals-Optimization/.github/workflows/compress-folders.yml)](https://github.com/MiaowCham/Vibrant-Visuals-Optimization/actions/workflows/compress-folders.yml)
[![Release](https://img.shields.io/github/v/release/MiaowCham/Vibrant-Visuals-Optimization?include_prereleases&sort=semver)](https://github.com/MiaowCham/Vibrant-Visuals-Optimization/releases)

> [!WARNING]
> English readme is still under construction!

<div align=center>

A Resource packs For Vibrant Visuals in Minecraft BE，Modify the unreasonable parameters in the original Vibrant Visuals through resource packs

Effectiveness is not guaranteed. Resource packs have limited modification capabilities, and Vibrant Visuals is still in development. Please refer to Mojang's official updates for the most accurate information.

Enabling "Render Dragon Feature for Creaters" to Enable all features!

</div>

## **This resource pack consists of<br>a main pack and multiple add-on packs**
### [Main Pack](./Main%20Pack/)
- Added multiple point light source
- Slightly increased natural light brightness to enhance visibility underwater/underground
- Upgraded vanilla 16x shadow resolution to 32x
- Reduced chlorophyll value to avoid the vanilla "nuclear wastewater" effect underwater
- **The resource plan needs to be set to the bottom**
### Addon Packs
|#|Name|Introduce|
|-|-|-|
1|[16x Shadows Recover Pack](./16x%20Shadows%20Recover%20Pack/)|将阴影分辨率恢复到16x<br>**无法与高清阴影附加包同时使用**|
2|[Clear Water Addon](./Clear%20Water%20Addon/)|启用水面波浪，同时关闭了水底焦散|
3|[Lighting Enhancement Addon](./Lighting%20Enhancement%20Addon/)|大幅提升了无光源处亮度|
4|[Soft Shadows Addon](./Soft%20Shadows%20Addon/)|将阴影类型修改为“软阴影”<br>**无法与16x阴影恢复包同时使用**|
5|[Water Caustics disabled Pack](./Water%20Caustics%20disabled%20Pack/)|关闭了水底焦散效果|
6|[Water Textures Addon](./Water%20Textures%20Addon/)|添加了Vibrant Visuals原版水面纹理和法线PBR<br>用于补充没有水面材质的资源包<br>**该资源包需要置顶**|
7|[Water Waves Addon](./Water%20Waves%20Addon/)|启用了被关闭的水面波浪<br>启用后水面纹理会变淡<br>**无法与水底焦散关闭包同时使用**|

## How To Use?
请先前往 [Actions](https://github.com/MiaowCham/Vibrant-Visuals-Optimization/actions/workflows/compress-folders.yml) 下载构建版，
或者前往 [Releases](https://github.com/MiaowCham/Vibrant-Visuals-Optimization/releases) 发行版文件<br>
将下载得到的 `mcpack-files.zip` 解压，将解压得到的 `.mcpack` 文件使用 Minecraft 打开即可导入
### 1.21.80 正式版已经支持灵动视效
- Windows
    - 右键 `.mcpack` 文件，选择使用 Minecraft 打开
    - 若点击 `选择其他应用`，在弹出的窗口选择 Minecraft 并点击 `始终` 即可将 Minecraft 作为默认打开方式
    - 请确保您使用的是 Minecraft 且版本号高于 `1.21.80`
- Android
    - 系统自带文件管理
      - 在文件管理中找到 `mcpack-files.zip` 并解压
      - 点击解压得到的 `.mcpack`，选择其他类型（若没有则一般选择文本类型）
      - 在弹出的窗口选择 Minecraft
      - 点击 `总是` 等选项可将 Minecraft 设为默认打开方式
    - MT 管理器/NP 管理器（推荐）
      - 在 MT/NP 管理器找到 `mcpack-files.zip` 并解压
      - 长按解压得到的 `.mcpack`，在弹出的菜单选择 `打开方式...`
      - 点击左下角 `类型` 按钮，选择 `全部` 选项
      - 在弹出的窗口选择 Minecraft
      - 长按 Minecraft 可选择设为默认打开方式
    - 需确保您的 Minecraft 版本号高于 `1.21.80`
- Linux
    - Linux Bedrock Launcher 暂不支持带有 Vibrant Visuals 的版本，具体导入方法参考Windows
- iOS / iPadOS
    - 煮啵太穷了买不起 Apple，自己去搜教程吧（悲

## LICENSE
This project uses the CC0-1.0 license
