# A high performance fork of Tuinity
# 这是 `StarCraft` 的 内部项目 
## Based on Tuinity Minecraft 1.16.5
## 你可以在[这里](https://github.com/StarCraftOffical/StarTuinity/releases/tag/CI)下载最近构建版

---

## 功能 | Feature
- 去除 Timings
- 实体AI半异步
- 语言汉化

## 构建 | Build
Clone本仓库后，使用 `Git Bash` 键入一下命令
```shell
./startuinity jar
```
等待运行完成后，你可以在 `/StarTuinity-Server/target` 下找到构建文件

## 开发 | Develop
Clone本仓库后，使用 `Git Bash` 键入以下命令
```shell
./startuinity jar
./startuinity patch
```
等待命令运行完成后，你就可以在 `/StarTuinity-Server` 和 `/StarTuinity-API` 中修改代码<br>
修改完后，请先 `commit` 修改的文件，再在 `Git Bash` 中运行
```shell
./startuinity rebuild # 生成 Patch
./startunity jar # 构建 Jar
```
随后，你就可以在 `/StarTuinity-Server/target` 下找到构建文件
运行 `rebuild` 后，请再次 `commit` 生成的 `.patch` 文件并 `push` 以同步更改
