![Vibrant Visuals Optimization](/Main%20Pack/Sample%20image.png)
<div align=center>

# Vibrant Visuals Optimization

[English](./README.md) / 简体中文

为《我的世界》基岩版 灵动视效 制作的优化资源包系列，通过资源包的方式修改原版 Vibrant Visuals 阴间参数

不保证一定可用/生效，资源包修改能力有限，且 Vibrant Visuals 还处于开发阶段，一切请以 Mojang 官方为准

建议开启 `为创建者提供的渲染龙功能` 以启用全部特性！

</div>

## 本资源包分为一个主包和多个附加包

### [主资源包 Main Pack](./Main%20Pack/)
- 添加多种点光源
- 轻微提高自然光亮度以提升水底/地底的亮度
- 将原版16x阴影分辨率提升至32x
- 降低 chlorophyll 值，避免原版“核废水”级水下效果
- **该资源包需要置底**
### 附加包 Addon Packs
|#|名称 / 对应英文名称|简介|
|-|-|-|
1|[16x阴影恢复包<br>16x Shadows Recover Pack](./16x%20Shadows%20Recover%20Pack/)|将阴影分辨率恢复到16x<br>**无法与高清阴影附加包同时使用**|
2|[干净水体拓展包<br>Clear Water Addon](./Clear%20Water%20Addon/)|启用水面波浪，同时关闭了水底焦散|
3|[暗处增强拓展包<br>Lighting Enhancement Addon](./Lighting%20Enhancement%20Addon/)|大幅提升了无光源处亮度|
4|[高清阴影附加包<br>Soft Shadows Addon](./Soft%20Shadows%20Addon/)|将阴影类型修改为“软阴影”<br>**无法与16x阴影恢复包同时使用**|
5|[水底焦散关闭包<br>Water Caustics disabled Pack](./Water%20Caustics%20disabled%20Pack/)|关闭了水底焦散效果|
6|[水面纹理拓展包<br>Water Textures Addon](./Water%20Textures%20Addon/)|添加了Vibrant Visuals原版水面纹理和法线PBR<br>用于补充没有水面材质的资源包<br>**该资源包需要置顶**|
7|[水面波浪拓展包<br>Water Waves Addon](./Water%20Waves%20Addon/)|启用了被关闭的水面波浪<br>启用后水面纹理会变淡<br>**无法与水底焦散关闭包同时使用**|

## 如何使用?
请先前往 [Actions](https://github.com/MiaowCham/Vibrant-Visuals-Optimization/actions/workflows/compress-folders.yml) 下载构建版，
或者前往 [Releases](https://github.com/MiaowCham/Vibrant-Visuals-Optimization/releases) 发行版文件

将下载得到的 `mcpack-files.zip` 解压，将解压得到的 `.mcpack` 文件使用 Minecraft Preview/Beta 打开即可导入<br>
- Windows设备 
    - 右键 `.mcpack` 文件，选择使用 Minecraft Preview 打开
    - 若点击 `选择其他应用`，在弹出的窗口选择 Minecraft Preview 并点击 `始终` 即可将 Minecraft Preview 作为默认打开方式
    - 请确保您使用的是 Minecraft Preview 且版本号高于 `1.21.80.25`
- Android设备 
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
    - 需确保您的 Minecraft 为 Beta 版且版本号高于 `1.21.80.25`
- Linux设备
    - Linux Bedrock Launcher 暂不支持带有 Vibrant Visuals 的版本，具体导入方法参考Windows
- iOS/iPadOS设备
    - 煮啵太穷了买不起 Apple，自己去搜教程吧（悲

## 许可证
本项目使用 CC0-1.0 许可证
