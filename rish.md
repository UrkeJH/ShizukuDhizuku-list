# Rish shell 中文说明

`rish` 是一个 Android 可执行文件（非应用），用于与运行在高层级特权守护进程中的 shell 进行交互。
例如，如果 Shizuku 是通过 ADB 权限启动的，那么 `rish` 也会提供一个保持 ADB 权限的 shell。

## 设置

要设置 `rish`，请打开 Shizuku，导航至“在终端应用中使用 Shizuku”，然后按照设置说明进行操作。请注意，要高效使用此功能，你需要具备 shell、终端和基本命令的基础知识。

`rish` 设置完成后，你可以将其与任何支持调用 shell 脚本或可执行文件的应用一起使用，即使该应用本身不支持 Shizuku 也可以。

> **注意**
> 
> 由于 `rish` 的位置不在 `$PATH` 环境变量中，手动启动时你可能需要指定可执行文件的路径。如果它位于当前工作目录中，请使用 `./rish` 来启动它。

## 语法

*   `rish`：启动默认的交互式 shell（使用 /system/bin/sh）
*   `rish exec /path/to/custom/shell`：启动自定义/替代的交互式 shell
*   `rish -c 'whoami'`：执行 shell 命令，完成后退出
*   `echo 'whoami' | rish`：从标准输入读取 shell 命令，执行它，完成后退出

> **注意**
> 
> 这里使用 `whoami` 作为示例命令，它会返回当前 shell 用户的名称。

## 使用示例

*   在像 **Termux** 这样的终端模拟器中，直接在您的设备上打开一个交互式 ADB shell
*   使用像 **Tasker** 这样的自动化应用，在后台自动触发高权限 ADB shell 命令
    *   示例：命令 `rish -c 'reboot'` 将通过 shell 使用 Shizuku 重启设备

## 官方文档

官方 rish 文档可在此处查看：[https://github.com/RikkaApps/Shizuku-API/blob/master/rish/README.md](https://github.com/RikkaApps/Shizuku-API/blob/master/rish/README.md)


​