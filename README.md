# 使用github的acthon编译lede

I18N: [English](README_EN.md) | [简体中文](README.md)

使用github actions 编译lede的OpenWrt [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)   
**1. 前提**
  - 登陆 [GitHub Actions](https://github.com/features/actions/signup)
  - Fork [这个仓库](https://github.com/LeeHe-gif/AutoBuild-LEDE.git)
    
**2. 编译固件**
  - 点击repo顶部的 `[.github/workflows]`文件夹，您可以看到几个工作流文件，每个文件对应一个特定架构的设备。
  - ***`UPDATED`*** 点击菜单上的“run workflow”，点击左侧您要编译的设备，然后转到右侧的“run workflow”按钮，点击下拉菜单上的绿色按钮“运行工作流“就行了！！！

  - 构建将自动启动。可以在“Actions”页面上查看进度。

  - 构建完成后，会自动按照时间发布release，在release中下载对应格式的固件。

  - 默认Web管理员IP:`192.168.10.1`，用户名`root`，无登陆密码。
