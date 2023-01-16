# Shiroha

---

### 功能 | Feature
- 去除 Timings
- 实体AI半异步
- 语言汉化
<br>

### 构建 | Build
`clone` 本仓库后，使用 `Git Bash` 键入一下命令
```shell
./shiroha jar
```
等待运行完成后，你可以在 `/Shiroha-Server/target` 下找到构建文件
<br>

### 开发 | Develop
`clone` 本仓库后，使用 `Git Bash` 键入以下命令
```shell
./shiroha jar
./shiroha patch
```
等待命令运行完成后，你就可以在 `/Shiroha-Server` 和 `/Shiroha-API` 中修改代码<br>
修改完后，请先 `commit` 修改的文件，再在 `Git Bash` 中运行
```shell
./shiroha rebuild # 生成 Patch
./shiroha jar # 构建 Jar
```
随后，你就可以在 `/Shiroha-Server/target` 下找到构建文件
运行 `rebuild` 后，请再次 `commit` 生成的 `.patch` 文件并 `push` 以同步更改
<br>
