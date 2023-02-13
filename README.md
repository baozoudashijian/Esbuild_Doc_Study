# esbuild get start

## 发现esbuild
+ esbuild是一个.exe文件，也就是一个可执行的文件
+ 明令行的三种形式
    + --foo（--minify是否启用某种标志）
    + --foo=bar（--platform单个值指定一次的标志）
    + --foo:bar（--external指定多个值）

## 启动项目时候的bug
+ esbuild命令不能执行（因为在此系统因为在此系统上禁止运行脚本)
    + 管理员运行powershell
    + 使用命令更改计算机的执行策略
+ vscode terminal 打开的一直是powershell，我们需要打开的是bash
    + 在terminal中直接输入bash