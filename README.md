> [!IMPORTANT]
> 本项目只收集支持Shizuku或Dhizuku的开源软件
> 
> 部分中文介绍是机翻,可能有误,见谅
> 
> 欢迎 fork and issue


## 语言
#### [繁體中文](https://github.com/lovestoryhhh/ShizukuDhizuku-list/blob/main/README-tw.md)

## Shizuku介绍
Shizuku 可以帮助普通应用借助一个由 app_process 启动的 Java 进程直接以 adb 或 root 特权使用系统 API

[Shizuku激活教程](shizuku教程.md)
[官方网站](https://shizuku.rikka.app/)

## Dhizuku介绍
参考Shizuku的设计思想，分享 DeviceOwner (设备所有者) 权限给其余应用

[Dhizuku激活教程](https://github.com/iamr0s/Dhizuku/discussions/16)

## Shizuku/Dhizuku下载地址
- [Dhizuku(原版)](https://github.com/iamr0s/Dhizuku) <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/iamr0s/Dhizuku?style=flat"></sub><sub><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/iamr0s/Dhizuku?style=social"></sub>

- [Shizuku(原版)](https://github.com/RikkaApps/Shizuku) <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/RikkaApps/Shizuku?style=flat"></sub><sub><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/RikkaApps/Shizuku?style=social"></sub>
<details open>
<summary>Shizuku改版</summary>

- [Shizuku(yangFenTuoZi)](https://github.com/yangFenTuoZi/Shizuku) <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/yangFenTuoZi/Shizuku?style=flat"></sub><sub><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/yangFenTuoZi/Shizuku?style=social"></sub>
    <details>
    <summary>新增功能</summary>

    - 在 userdebug ROM 上启用 ADB root 权限
    - 支持非 Root 设备自启动
    - 支持自定义 ADB TCP/IP 端口
  
    </details>


- [Shizuku(pixincreate)](https://github.com/pixincreate/Shizuku) <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/pixincreate/Shizuku?style=flat"></sub><sub><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/pixincreate/Shizuku?style=social"></sub>
    <details>
    <summary>新增功能</summary>

    - **Auto-start**: This fork provides an auto-start feature on root-less devices that allows the Shizuku service to start automatically on boot. This is useful for users who want to ensure that the service is always running without manual intervention.
    - **Rooted-Debugging**: This fork allows you to debug the Shizuku service while it is running with root privileges. This feature is only available on `userdebug` and `eng` builds of Android.
    - **Stealth**: Prevent Shizuku from being detected by other apps. This is done by randomizing the Shizuku tmp folder name and also by deleting the starter file after the service is started.
  
    </details>

- [Shizuku(thedjchi)](https://github.com/thedjchi/Shizuku) <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/thedjchi/Shizuku?style=flat"></sub><sub><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/thedjchi/Shizuku?style=social"></sub>
    <details>
    <summary>新增功能</summary>

    * **More robust "start on boot":** waits for a Wi-Fi connection before starting the Shizuku service
    * **TCP mode:** (i.e., the `adb tcpip` command) once Shizuku successfully starts with Wi-Fi after a reboot, you can stop/restart Shizuku without a Wi-Fi connection!
    * **Watchdog service:** automatically restarts Shizuku if it stops unexpectedly, and can alert you of crashes/potential fixes
    * **Start/stop intents:** toggle Shizuku on-demand using automation apps (e.g., Tasker, MacroDroid, Automate)
    * **[BETA] Stealth mode:** hide Shizuku from other apps that don't work when Shizuku is installed
    * **[BETA] In-app updates:** option to automatically check for new updates, and can automatically download/install the latest version from GitHub
    * **Android/Google TV and VR headset support:** UI is now compatible with D-Pad remotes, all TVs are supported (including Android 14+ TVs that require pairing), and the multi-window pairing dialog is toggleable in settings for VR headsets
    * **MediaTek support:** fixes a critical bug in the original v13.6.0 which preve
  
    </details>

</details open>

<details open>
    <summary>Shizuku特殊分支</summary>

- [Stellar](https://github.com/roro2239/Stellar) 一个基于 Shizuku 的魔改分支，让应用通过 ADB 或 Root 权限使用系统级 API  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/roro2239/Stellar?style=flat"></sub><sub><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/roro2239/Stellar?style=social"></sub>
  
</details open>

## 支持软件
<details open>
<summary style="font-size:18px">软件管理</summary>

- [雹](https://github.com/aistra0528/Hail) `Shizuku/Dhizuku/Root/adb` 一款用于冻结 Android 应用的自由软件  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/aistra0528/Hail?style=flat"></sub>

- [Canta](https://github.com/samolego/Canta) `Shizuku` 在没有root权限的情况下卸载任何Android应用  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/samolego/Canta?style=flat"></sub>

- [Package Manager](https://github.com/SmartPack/PackageManager) `Shizuku/adb` 管理安装在android设备上的系统和app  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/SmartPack/PackageManager?style=flat"></sub>

- [Island](https://github.com/oasisfeng/island) `Shizuku/Dhizuku(DAX)` 隔离和克隆应用程序以保护隐私和并行运行  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/oasisfeng/island?style=flat"></sub>
    <details open>
    <summary>注意事项</summary>
    Island在Dhizuku激活情况下,可能无法使用,但是有概率通过卡bug使用(具体教程可在酷安等平台寻找)
    </details>
    <details open>
    <summary>相似软件</summary>

    - [Insular](https://gitlab.com/secure-system/Insular) `Shizuku/Dhizuku(DAX)` island的分支软件
  
    </details>

- [Inure](https://github.com/Hamza417/Inure) `Shizuku` 优雅的Android应用程序管理器  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Hamza417/Inure?style=flat"></sub>

- [Blocker](https://github.com/lihenggui/blocker) `Shizuku/Root` 操作Android应用程序四大组件的程序  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/lihenggui/blocker?style=flat"></sub>

- [Shappky](https://github.com/YasserNull/shappky) `Shizuku` kill或阻止后台应用程序,提高设备性能  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/YasserNull/shappky?style=flat"></sub>

- [Thor](https://github.com/trinadhthatakula/Thor) `Shizuku` 应用程序管理器  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/trinadhthatakula/Thor?style=flat"></sub>

- [MMRL](https://github.com/MMRLApp/MMRL) `Shizuku(Root)` 管理模块存储库  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/MMRLApp/MMRL?style=flat"></sub>

- [AppControlX](https://github.com/risunCode/AppControl-X) `Shizuku/Root` 一款强大的安卓应用，用于控制应用行为、系统监控和设备管理  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/risunCode/AppControl-X?style=flat"></sub>

- [Rootless Store](https://github.com/Resilien-Mobile/RootlessStore) `Shizuku/Root/adb` 一个开源的、面向安卓生态的 Rootless 插件管理与运行平台  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Resilien-Mobile/RootlessStore?style=flat"></sub>

- [Running Services Monitor](https://github.com/biplobsd/running_services_monitor) `Shizuku` 监控安卓设备上正在运行的服务  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/biplobsd/running_services_monitor?style=flat"></sub>

</details>

<details open>
<summary style="font-size:18px">终端</summary>

- [aShell You](https://github.com/DP-Hridayan/aShellYou) `Shizuku/Root/adb` Material You 风格的 aShell 应用程序  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/DP-Hridayan/aShellYou?style=flat"></sub>

- [ReTerminal](https://github.com/RohitKushvaha01/ReTerminal) `Shizuku` 时尚的、Material3风格的终端模拟器  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/RohitKushvaha01/ReTerminal?style=flat"></sub>

- [Haven](https://github.com/GlassHaven/Haven) `Shizuku` Android SSH、VNC、RDP 和 SFTP 客户端 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/GlassHaven/Haven?style=flat"></sub>

- [Termux](https://github.com/termux/termux-app) `Shizuku` 适用于Android操作系统的终端模拟器应用 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/termux/termux-app?style=flat"></sub>
    <details open>
    <summary>注意事项</summary>

    需要使用[rish](rish.md)
    可参考[教程(bilibili)](https://www.bilibili.com/video/BV15Qa9eSEhP/)
    
    </details>

</details>

<details open>
<summary style="font-size:18px">文件管理</summary>

- [SD Maid SE](https://github.com/d4rken-org/sdmaid-se) `Shizuku/Root` Android文件管理工具，释放空间和删除不需要的数据 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/d4rken-org/sdmaid-se?style=flat"></sub>

- [fluffy](https://github.com/mlm-games/fluffy) `Shizuku` 具有强大的存档支持和适合 Android TV 界面的文件管理器 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/mlm-games/fluffy?style=flat"></sub>

- [NFile](https://github.com/Senzme/NFile) `Shizuku` 漂亮的文件管理器 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Senzme/NFile?style=flat"></sub>

- [ZenFile](https://github.com/l930203811/ZenFile) `Shizuku` 现代化安卓文件管理器 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/l930203811/ZenFile?style=flat"></sub>

</details>

<details open>
<summary style="font-size:18px">隐私保护</summary>

- [Amarok-Hider](https://github.com/deltazefiro/Amarok-Hider) `Shizuku/Dhizuku/Root` 轻量级隐私保护工具，一键隐藏你的隐私文件和应用  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/deltazefiro/Amarok-Hider?style=flat"></sub>

- [App Lock](https://github.com/PranavPurwar/AppLock) `Shizuku` 开源 Android 应用锁工具，主打隐私保护与敏感数据防护  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/PranavPurwar/AppLock?style=flat"></sub>
  
- [KeyAttestation](https://github.com/vvb2060/KeyAttestation) `Shizuku` 支持生成、保存、加载、解析和验证Android密钥和ID证明数据  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/vvb2060/KeyAttestation?style=flat"></sub>

- [PrivacyFlip](https://github.com/dorumrr/privacyflip) `Shizuku/Root` Android 设备的自动锁定/解锁隐私控制  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/dorumrr/privacyflip?style=flat"></sub>

- [Android AntiForensic Tools](https://github.com/bakad3v/Android-AntiForensic-Tools) `Shizuku` 保护用户数据免受侵害  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/bakad3v/Android-AntiForensic-Tools?style=flat"></sub>
</details>

<details open>
<summary style="font-size:18px">娱乐</summary>

- [Mihon](https://github.com/mihonapp/mihon) `Shizuku/Root` 功能齐全的漫画阅读器   <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/mihonapp/mihon?style=flat"></sub>

    <details open>
    <summary>相似软件</summary>

    - [TachiyomiSY](https://github.com/jobobby04/TachiyomiSY) `Shizuku/Root`  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/jobobby04/TachiyomiSY?style=flat"></sub>


    - [TachiyomiAZ](https://github.com/az4521/TachiyomiAZ) `Shizuku/Root`   <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/az4521/TachiyomiAZ?style=flat"></sub>


    - [Aniyomi](https://github.com/aniyomiorg/aniyomi) `Shizuku/Root`   <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/aniyomiorg/aniyomi?style=flat"></sub>

    </details>

- [HLB站缓存合并](https://github.com/molihuan/hlbmerge_flutter) `Shizuku` Bilibili缓存视频合并工具  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/molihuan/hlbmerge_flutter?style=flat"></sub>

- [BILIBILIAS](https://github.com/1250422131/bilibilias) `Shizuku` 第三方的B站视频缓存工具  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/1250422131/bilibilias?style=flat"></sub>

- [Recent Apps TV](https://github.com/Qutaiba-Khader/RecentAppsTV) `Shizuku` 轻量级 的 Android TV 和 Google TV  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Qutaiba-Khader/RecentAppsTV?style=flat"></sub>

</details>

<details open>
<summary style="font-size:18px">设备所有者</summary>

- [OwnDroid](https://github.com/BinTianqi/OwnDroid) `Shizuku/Dhizuku/adb` 使用安卓Device owner特权管理你的设备  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/BinTianqi/OwnDroid?style=flat"></sub>
    <details open>
    <summary>相似软件</summary>

    - [MDPC](https://github.com/MrRare2/MDPC) `Shizuku` OwnDroid 的分支,增加了一些功能  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/MrRare2/MDPC?style=flat"></sub>
    </details>

</details>

<details open>
<summary style="font-size:18px">定制</summary>

- [SystemUI Tuner](https://github.com/zacharee/Tweaker) `Shizuku` 查看和修改Android设备上隐藏设置的应用程序  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/zacharee/Tweaker?style=flat"></sub>

- [ColorBlendr](https://github.com/Mahmud0808/ColorBlendr) `Shizuku` 用于在搭载Android 12+设备上自定义Material You颜色的Android应用 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Mahmud0808/ColorBlendr?style=flat"></sub>

- [Járngreipr](https://github.com/BrianJr03/Jarngreipr) `Shizuku` 现代化、可定制的安卓启动器 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/BrianJr03/Jarngreipr?style=flat"></sub>

- [ShizuTools](https://github.com/legendsayantan/ShizuTools) `Shizuku` 突破 Android 系统默认权限限制，提供多种实用系统管理功能  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/legendsayantan/ShizuTools?style=flat"></sub>

- [Adaptive Theme](https://github.com/xLexip/Adaptive-Theme) `Shizuku` 基于环境光传感器的安卓自动暗模式 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/xLexip/Adaptive-Theme?style=flat"></sub>

- [Language Selector](https://github.com/VegaBobo/Language-Selector) `Shizuku` 允许用户设置单独的应用程序语言  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/VegaBobo/Language-Selector?style=flat"></sub>

- [Krude](https://github.com/KusStar/krude) `Shizuku` 小而美的应用启动器  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/KusStar/krude?style=flat"></sub>

- [DroidOS](https://github.com/Katsuyamaki/DroidOS) `Shizuku` 拼贴窗口管理器，三星DEX替代品，弹出式应用启动器  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Katsuyamaki/DroidOS?style=flat"></sub>

- [Extendroid](https://github.com/legendsayantan/Extendroid) `Shizuku` Android 多任务管理器，支持桌面式多窗口和远程访问 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/legendsayantan/Extendroid?style=flat"></sub>

- [OmniPrompt](https://github.com/mrndstvndv/OmniPrompt) `Shizuku` 以键盘为先的安卓命令面板 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/mrndstvndv/OmniPrompt?style=flat"></sub>

- [Smart Edge](https://github.com/Imtiaz-Official/Smart-Edge) `Shizuku` 高度可定制的安卓侧面板 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Imtiaz-Official/Smart-Edge?style=flat"></sub>

- [YoukiDEX](https://github.com/mrYouki/YoukiDex-Android-Desktop) `Shizuku` 基于Smart Dock构建的完整Android桌面 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/mrYouki/YoukiDex-Android-Desktop?style=flat"></sub>

- [Carrier Vanity Name](https://github.com/nullbytepl/CarrierVanityName) `Shizuku` 在未root的安卓设备上更改运营商名称 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/nullbytepl/CarrierVanityName?style=flat"></sub>
</details>

<details open>
<summary style="font-size:18px">安装程序&应用商店</summary>

- [InstallerX Revived](https://github.com/wxxsfxyzm/InstallerX-Revived) `Shizuku/Dhizuku/Root` 应用安装程序  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/wxxsfxyzm/InstallerX-Revived?style=flat"></sub>

    <details open>
    <summary>相似软件</summary>

    - [PI](https://github.com/SanmerApps/PI) `Shizuku/Root` 覆盖系统默认安装程序和执行app安装程序  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/SanmerApps/PI?style=flat"></sub>


    - [Install with Options](https://github.com/zacharee/InstallWithOptions) `Shizuku` 应用安装程序  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/zacharee/InstallWithOptions?style=flat"></sub>


    - [PackageInstaller](https://github.com/vvb2060/PackageInstaller) `Shizuku` Android 的轻量级但功能强大的软件包安装程序  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/vvb2060/PackageInstaller?style=flat"></sub>

    - [Universal Installer](https://github.com/pass-with-high-score/universal-installer) `Shizuku` 现代的安卓包管理器，负责处理默认安装程序无法处理的内容  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/pass-with-high-score/universal-installer?style=flat"></sub>

    </details>

- [Obtainium](https://github.com/ImranR98/Obtainium) `Shizuku` 直接从源代码获取app更新  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/ImranR98/Obtainium?style=flat"></sub>

- [Komi Store](https://github.com/kurikomi-labs/komi-store) `Shizuku` 开发者发布应用商店 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/kurikomi-labs/komi-store?style=flat"></sub>

- [Orion Store](https://github.com/RookieEnough/Orion-Store) `Shizuku` 一个以 Android 为先的商店客户端，依赖于公共来源，而不是将一切隐藏在私有服务层之后  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/RookieEnough/Orion-Store?style=flat"></sub>

- [FFUpdater](https://github.com/Tobi823/ffupdater) `Shizuku` 更新注重隐私的浏览器和邮箱app  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Tobi823/ffupdater?style=flat"></sub>

- [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore) `Shizuku/Root` Google Play 商店的开源替代品

- [Droid-ify](https://github.com/Droid-ify/client) `Shizuku/Root` 第三方F-Droid 客户端  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Droid-ify/client?style=flat"></sub>
    <details open>
    <summary>相似软件</summary>

    - [flicky](https://github.com/mlm-games/flicky) `Shizuku` 第三方 F-Droid 客户端(适用于电视) <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/mlm-games/flicky?style=flat"></sub>

    - [Neo-Store](https://github.com/NeoApplications/Neo-Store) `Shizuku/Root` 现代且功能丰富的 F-Droid 客户端 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/NeoApplications/Neo-Store?style=flat"></sub>

    - [Florid](https://github.com/Nandanrmenon/florid) `Shizuku` Material3风格 F-Droid 客户端  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Nandanrmenon/florid?style=flat"></sub>
    </details>



<details open>
<summary style="font-size:18px">自动化&AI</summary>

- [AutoJs6](https://github.com/SuperMonster003/AutoJs6) `Shizuku` 支持无障碍服务的 JavaScript 自动化工具  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/SuperMonster003/AutoJs6?style=flat"></sub>

- [gkd](https://github.com/gkd-kit/gkd) `Shizuku` 自定义屏幕点击APP  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/gkd-kit/gkd?style=flat"></sub>

- [PhoneProfilesPlus](https://github.com/henrichg/PhoneProfilesPlus) `Shizuku` 允许自动或一键配置设备以适应生活情况  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/henrichg/PhoneProfilesPlus?style=flat"></sub>

- [Geto](https://github.com/JackEblan/Geto) `Shizuku` 启动特定应用时自动更改设备设置  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/JackEblan/Geto?style=flat"></sub>

- [Tarnhelm](https://github.com/lz233/Tarnhelm) `Shizuku` 清理共享链接的跟踪，支持自定义URL重写规则  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/lz233/Tarnhelm?style=flat"></sub>

- [DetoxDroid](https://github.com/flxapps/DetoxDroid) `Shizuku` 使用手机而不是让手机利用你   <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/flxapps/DetoxDroid?style=flat"></sub>

- [DigiPaws](https://github.com/nethical6/digipaws) `Shizuku` 帮助用户减少屏幕成瘾  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/nethical6/digipaws?style=flat"></sub>

- [Operit](https://github.com/AAswordman/Operit) `Shizuku/Root/adb` 移动端首个功能完备的 AI 智能助手应用,可以用Shizuku执行命令  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/AAswordman/Operit?style=flat"></sub>

- [Open-AutoGLM-Android](https://github.com/xinzezhu/Open-AutoGLM-Android) `Shizuku` 基于 Android 无障碍服务的智能手机自动化助手，使用 AutoGLM 视觉语言模型实现自然语言指令的手机操作  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/xinzezhu/Open-AutoGLM-Android?style=flat"></sub>

- [rish-mcp](https://github.com/turin-dev/rish-mcp) `Shizuku` 从AI中运行Android手机的Shizuku shell作为MCP工具 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/turin-dev/rish-mcp?style=flat"></sub>

- [AutoGLM](https://github.com/iamr0s/Ruto-GLM) `Shizuku` 强大的 Android 自动化和多任务框架 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/iamr0s/Ruto-GLM?style=flat"></sub>
</details>

<details open>
<summary style="font-size:18px">开发工具</summary>

- [LibChecker](https://github.com/LibChecker/LibChecker) `Shizuku` 查看设备中应用程序中使用的库  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/LibChecker/LibChecker?style=flat"></sub>

- [AndroidLowLevelDetector](https://github.com/imknown/AndroidLowLevelDetector) `Shizuku` 检测Treble,GSI,Mainline,APEX,system-as-root(SAR),A/B等  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/imknown/AndroidLowLevelDetector?style=flat"></sub>

- [LogFox](https://github.com/F0x1d/LogFox) `Shizuku` Android的LogCat阅读器  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/F0x1d/LogFox?style=flat"></sub>

- [Accounts](https://github.com/iamr0s/AndroidAccounts) `Shizuku` 查看可能存在账户的应用  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/iamr0s/AndroidAccounts?style=flat"></sub>

- [FrameX](https://github.com/MaheshSharan/FrameX-Android) `Shizuku` Android 实时性能检测 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/MaheshSharan/FrameX-Android?style=flat"></sub>

- [FPSViewer](https://github.com/binhmod/FPSViewer) `Shizuku` 在屏幕上实时显示帧数计数器 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/binhmod/FPSViewer?style=flat"></sub>

- [DSU Sideloader](https://github.com/VegaBobo/DSU-Sideloader) `Shizuku/Root` 帮助用户通过DSU轻松安装 GSI  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/VegaBobo/DSU-Sideloader?style=flat"></sub>

- [lspatch](https://github.com/JingMatrix/LSPatch) `Shizuku` 免root实现Xposed注入   <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/JingMatrix/LSPatch?style=flat"></sub>
    <details open>
    <summary>相似软件</summary>

    - [NPatch](https://github.com/7723mod/NPatch) `Shizuku` 复刻自LSPatch,以LSPosed为基础的免root的Xposed框架   <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/7723mod/NPatch?style=flat"></sub>

    </details>

- [Universal ReVanced Manager](https://github.com/Jman-Github/Universal-ReVanced-Manager) `Shizuku` ReVanced 补丁工具,包含一些额外功能   <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Jman-Github/Universal-ReVanced-Manager?style=flat"></sub>

- [Morphe](https://github.com/MorpheApp/morphe-manager) `Shizuku`  基于Universal-ReVanced-Manager的YouTube补丁工具  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/MorpheApp/morphe-manager?style=flat"></sub>
</details>


<details open>
<summary style="font-size:18px">网络</summary>

- [CatShare](https://github.com/kmod-midori/CatShare) `Shizuku` 通过蓝牙发送和接收文件  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/kmod-midori/CatShare?style=flat"></sub>

- [ADNS](https://github.com/eyalm2000/adns) `Shizuku` 基于Android的轻量级基于DNS的广告拦截器，内置NextDNS <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/eyalm2000/adns?style=flat"></sub>

- [sing-box](https://github.com/SagerNet/sing-box) `Shizuku` 通用代理平台  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/SagerNet/sing-box?style=flat"></sub>

- [WiFi Password Manager](https://github.com/Khh-vu/wifi-password-manager) `Shizuku/Root` 使用Shizuku或root权限来管理WiFi密码  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Khh-vu/wifi-password-manager?style=flat"></sub>

- [Kettu](https://github.com/C0C0B01/Kettu) `Shizuku`  Discord 模组工具  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/C0C0B01/Kettu?style=flat"></sub>

- [MastodonRedirect](https://github.com/zacharee/MastodonRedirect) `Shizuku` 解决Mastodon和Lemmy等联邦社交平台的深层链接问题，让用户能便捷地用首选客户端打开链接  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/zacharee/MastodonRedirect?style=flat"></sub>

- [TxtNet-Browser](https://github.com/lukeaschenbrenner/TxtNet-Browser) `Shizuku` 通过短信浏览网页，无需 WiFi 或移动数据  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/lukeaschenbrenner/TxtNet-Browser?style=flat"></sub>

- [delta](https://github.com/supershadoe/delta) `Shizuku` 热点管理器  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/supershadoe/delta?style=flat"></sub>

- [ShizuWall](https://github.com/AhmetCanArslan/ShizuWall) `Shizuku` 轻量级、注重隐私的 Android 防火墙应用程序  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/AhmetCanArslan/ShizuWall?style=flat"></sub>

- [EasySpot](https://github.com/EasySpotApp/EasySpot) `Shizuku` 允许你通过蓝牙远程开启热点  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/EasySpotApp/EasySpot?style=flat"></sub>
  
- [De1984](https://github.com/dorumrr/de1984) `Shizuku` 无需VPN的应用防火墙管理软件  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/dorumrr/de1984?style=flat"></sub>

- [WG Tunnel](https://github.com/wgtunnel/android) `Shizuku` 支持 FOSS WireGuard 和 AmneziaWG Android 的客户端，支持自动隧道、锁定和代理 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/wgtunnel/android?style=flat"></sub>
</details>

<details open>
<summary style="font-size:18px">音频</summary>

- [RootlessJamesDSP](https://github.com/timschneeb/RootlessJamesDSP) `Shizuku` 系统范围的 JamesDSP 音频处理引擎的实现,适用于非 root 的 Android 设备  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/timschneeb/RootlessJamesDSP?style=flat"></sub>

- [Volume Manager](https://github.com/yume-chan/VolumeManager) `Shizuku` 独立控制每个应用程序的音量  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/yume-chan/VolumeManager?style=flat"></sub>

- [WEcho](https://github.com/qumolangmo/wecho) `Shizuku` 功能丰富的 Android 全局音效处理器 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/qumolangmo/wecho?style=flat"></sub>

- [MicUp](https://github.com/papergray/MicUp) `Shizuku` Android 实时麦克风音频处理  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/papergray/MicUp?style=flat"></sub>

</details>

<details open>
<summary style="font-size:18px">显示管理</summary>

- [Fold Switcher](https://github.com/eiyooooo/Fold_Switcher) `Shizuku` 折叠屏切换器  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/eiyooooo/Fold_Switcher?style=flat"></sub>

- [Grayscaler](https://github.com/C10udburst/Grayscaler) `Shizuku` 让您的手机保持大部分单色  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/C10udburst/Grayscaler?style=flat"></sub>

</details>

<details open>
<summary style="font-size:18px">电源管理</summary>

- [dumpsys-battery-manager](https://github.com/superisuer/dumpsys-battery-manager) `Shizuku` 通过 dumpsys 与接口更改电池值  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/superisuer/dumpsys-battery-manager?style=flat"></sub>

- [ScreenOff](https://github.com/WuDi-ZhanShen/ScreenOff) `Shizuku` 控制您的 Android 屏幕 显示或不显示  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/WuDi-ZhanShen/ScreenOff?style=flat"></sub>

- [ZukuLock](https://github.com/tiendnm/zukulock) `Shizuku` 快速打开或关闭屏幕  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/tiendnm/zukulock?style=flat"></sub>

- [RebootNya](https://github.com/daisukiKaffuChino/RebootNya) `Shizuku/Root` 一款简单而先进的重启应用程序   <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/daisukiKaffuChino/RebootNya?style=flat"></sub>

- [EnforceDoze](https://github.com/farfromrefug/EnforceDoze) `Shizuku` 屏幕关机后立即启用休眠模式  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/farfromrefug/EnforceDoze?style=flat"></sub>
</details>

<details open>
<summary style="font-size:18px">输入法</summary>

- [KeyMapper](https://github.com/keymapperorg/KeyMapper) `Shizuku` 改变键盘按钮在你设备上的作用  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/keymapperorg/KeyMapper?style=flat"></sub>

- [XtMapper](https://github.com/Xtr126/XtMapper) `Shizuku` 适用于 Android x86 的键盘  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Xtr126/XtMapper?style=flat"></sub>

- [KeySync](https://github.com/aka-munan/keysync) `Shizuku` 允许用户使用外接键盘和鼠标玩游戏  <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/aka-munan/keysync?style=flat"></sub>

- [TitanPad](https://github.com/sztupy/TitanPad) `Shizuku` 键盘的电容传感器当作触控板，在屏幕上移动虚拟鼠标等 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/sztupy/TitanPad?style=flat"></sub>

- [Pastiera](https://github.com/palsoftware/pastiera) `Shizuku` 专为PKB设备设计的安卓键盘 <sub><img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/palsoftware/pastiera?style=flat"></sub>

</details>

## 致谢
项目中有所借鉴
### [awesome-shizuku](https://github.com/timschneeb/awesome-shizuku)

## 附注
`Shizuku(Root)`: 需要 Shizuku 在 Root 模式下运行

`Dhizuku(DAX)`: 软件注入DAX模块后,可支持Dhizuku

`adb`: 支持adb指令激活

`Shizuku/Dhizuku/Root`: 支持 Shizuku/Dhizuku/Root 多种模式
