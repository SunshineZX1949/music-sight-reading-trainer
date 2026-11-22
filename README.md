[简体中文](README.md) | [English](README.en-US.md)
# 谱读 · 五线谱识谱练习

单文件、离线可用的钢琴识谱练习网页。

## 使用

直接用浏览器打开：

- `dist/piano-sight-reading.html`（分发版）
- `index.html`（源文件，内容与分发版一致）


## 目录

- `index.html` / `dist/piano-sight-reading.html` —— 自包含网页，字体已内嵌
- `assets/music-subset.woff2`、`assets/music-subset.b64` —— 内嵌字体的源文件
- `assets/LICENSE-NOTO-MUSIC.txt` —— Noto Music 字体许可

## 功能

- 高音谱、低音谱、大谱表切换
- 自由选择练习音区
- 0–7 个升号的调号练习
- 标准黑白高光钢琴键，支持横向滚动
- 答错时以红色音符在谱表上标出错音，并高亮正确琴键
- 当前、白色、黑色三种界面风格
- 自动检查浏览器语言：中文浏览器显示中文，其他语言显示英文
- 设置中可手动切换“自动 / 中文 / English”，选择会保存在本机
