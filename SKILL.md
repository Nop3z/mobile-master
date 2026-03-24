---
name: mobile-master
description: 移动安全SKILL 协助逆向
---



1. 

2. 拉取apk (if necessary)

运行脚本 [script](./scripts/Extract-Installation-Package.sh)

## Commands

### spawn模式 attach模式 dexdump frida检测绕过 脱壳 jadx-gui apktool 重签名


## 启动frida-server

运行脚本 [script](./scripts/Start-frida-server.sh) 以启动frida-server

## 拉取apk (if necessary)

运行脚本 [script](./scripts/Extract-Installation-Package.sh)

## spawn APP

运行脚本 [script](./scripts/spawn-app.sh)

## attach APP

运行脚本 [script](./scripts/attach-app.sh)

## dexdump

运行脚本 [script](./scripts/Dexdump.sh)

## jadx-gui

运行命令 `jadx-gui ./dexdump/*`