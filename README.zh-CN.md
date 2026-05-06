# SwineSync Studio

这是 `SwineSync Studio` 桌面打包版的公开发布仓库。

这个仓库用于**二进制程序分发**，不是开源源码仓库。

## 关联仓库

- 开源配套仓库：[SwineSync-OpenSource](https://github.com/zengzhengcheng/SwineSync-OpenSource)
- 打包版发布仓库：[SwineSync-Studio](https://github.com/zengzhengcheng/SwineSync-Studio)

## 用户需要下载的文件

请在 Releases 页面下载以下文件：

- `main.exe`
- `trabase_model.onnx.enc`
- `tragan_model.onnx.enc`
- `traganbase_model.onnx.enc`
- `first.obj`

下面这个空白占位文件直接放在仓库目录里：

- `release_layout/userModels/初始模型.obj`

## 正确目录结构

下载后请按下面方式摆放文件：

```text
SwineSync-Studio/
|-- main.exe
|-- models/
|   |-- trabase_model.onnx.enc
|   |-- tragan_model.onnx.enc
|   `-- traganbase_model.onnx.enc
`-- userModels/
    |-- first.obj
    `-- 初始模型.obj
```

## 使用提醒

- 软件第一次运行时，比较容易被杀毒软件拦截或查杀，建议提前提醒用户。
- 软件第一次运行需要联网。
- 软件每 10 次运行也需要联网一次。
- 软件一旦运行过，就不要再挪动文件位置。
- 如果用户挪动了位置，建议重新下载软件。
- 如果用户需要多开，请在不同文件位置分别再下载一份。
- 这个打包版本在 `2027-05-05` 后停止使用。
- 我们会在每次发布新版本时更新软件的截止日期。
- 这样设计的目的是鼓励用户持续使用最新版本，因为新版本会持续加入新功能、优化和修复。

## 仓库范围

这个仓库只负责发布打包后的程序文件。

- 不作为主要源码仓库使用
- 开源处理代码请查看 `SwineSync-OpenSource`
