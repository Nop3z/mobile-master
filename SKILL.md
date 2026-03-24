---
name: mobile-master
description: 移动安全SKILL 协助逆向
---



1. 

2. 拉取apk (if necessary)

运行脚本 [script](./scripts/Extract-Installation-Package.sh)

## Commands

### spawn模式 attach模式 dexdump frida检测绕过 脱壳 jadx-gui apktool 重签名

## jadx-gui

运行命令 `jadx-gui ./dexdump/*`

## Suport commands

| Script  | Description |
|---------|-------------|
| [Start-frida-server](./scripts/Start-frida-server.sh)| 启动设备上的frida-server |
| [Extract-Installation-Package](./scripts/Extract-Installation-Package.sh) | 从设备提取安装包APK |
| [spawn-app](./scripts/Spawn-app.sh) | spawn模式启动应用进行hook |
| [attach-app](./scripts/attach-app.sh) | attach模式附加到运行中的应用 |
| [Dexdump](./scripts/Dexdump.sh) | 内存dump dex文件脱壳 |