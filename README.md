# Wolai Theme

一个受 [Wolai](https://www.wolai.com) 设计风格启发的 Obsidian 主题，追求简洁、现代的笔记体验。

## 特性

- 干净简洁的视觉风格，减少视觉干扰
- 支持亮色 / 暗色双模式
- 中文字体优化（PingFang SC、Microsoft YaHei）
- 舒适的行距与排版，适合长时间阅读
- 优化的代码块、表格、引用块样式
- 圆角卡片式 UI 元素

## 安装

### 手动安装

1. 下载 `theme.css` 和 `manifest.json`
2. 将文件放入你的 Obsidian vault 的 `.obsidian/themes/Wolai Theme/` 目录
3. 打开 Obsidian → 设置 → 外观 → 主题，选择 **Wolai Theme**

### 通过社区主题市场（待发布）

1. 打开 Obsidian → 设置 → 外观 → 主题 → 管理
2. 搜索 **Wolai Theme**，点击安装

## 截图

*暗色模式和亮色模式截图待补充*

## 开发

```bash
# 克隆仓库
git clone https://github.com/diya/obsidian-wolai-theme.git

# 将主题软链接到你的 vault（替换路径）
ln -s $(pwd) "/path/to/your/vault/.obsidian/themes/Wolai Theme"
```

修改 `theme.css` 后刷新 Obsidian（Ctrl/Cmd+R）即可预览效果。

## License

MIT
