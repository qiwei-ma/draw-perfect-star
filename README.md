# 画一个完美的五角星 ⭐

一个有趣的在线绘画挑战游戏，测试你的手部稳定性和绘画技巧！

## 🎮 游戏介绍

这是一个简单但极具挑战性的绘画游戏，灵感来自于"Draw a Perfect Circle"。玩家需要用鼠标或触摸屏尽可能准确地画出一个五角星，系统会根据你画的形状与完美五角星的相似度来打分。

## ✨ 特性

- 🎯 **精准挑战** - 测试你的手部稳定性和绘画技巧
- 🏆 **记录最高分** - 自动保存你的最佳成绩
- 📱 **多设备支持** - 完美支持桌面和移动设备
- 🎨 **视觉反馈** - 根据得分显示不同颜色的反馈
- ⚡ **即时评分** - 实时计算并显示你的准确度
- 💫 **精美动画** - 流畅的动画效果和粒子背景

## 🚀 快速开始

### 在线游戏

访问 [https://qiwei-ma.github.io/draw-perfect-star/](https://qiwei-ma.github.io/draw-perfect-star/) 立即开始游戏！

### 本地运行

1. 克隆此仓库：
```bash
git clone https://github.com/qiwei-ma/draw-perfect-star.git
cd draw-perfect-star
```

2. 使用任何 HTTP 服务器运行，例如：
```bash
# 使用 Python
python -m http.server 8000

# 或使用 Node.js
npx http-server
```

3. 在浏览器中打开 `http://localhost:8000`

## 📖 游戏玩法

1. 打开游戏页面
2. 按住鼠标左键（或触摸屏幕）开始绘画
3. 尝试沿着虚线参考线画出完美的五角星
4. 松开鼠标（或手指）完成绘画
5. 查看你的得分！

## 🎯 评分系统

- **95% 以上** - 金色线条，完美！🏆
- **85-94%** - 绿色线条，非常好！✨
- **70-84%** - 橙色线条，不错！👍
- **70% 以下** - 红色线条，继续努力！💪

## 🛠️ 技术栈

- HTML5 Canvas
- 纯 JavaScript（无框架）
- CSS3 动画
- LocalStorage（保存最高分）
- Service Worker（支持 PWA）

## 📱 PWA 支持

本应用支持作为渐进式 Web 应用（PWA）安装到你的设备上，可以像原生应用一样使用！

## 🔧 部署到 GitHub Pages

1. Fork 这个仓库
2. 在仓库设置中启用 GitHub Pages，选择 main 分支
3. 如果使用不同的仓库名，需要修改代码中的所有 URL 引用
4. 访问 `https://你的用户名.github.io/仓库名/` 查看你的游戏！

## 📝 自定义配置

### 修改域名引用

如果使用不同的仓库名或域名，需要在以下文件中更新 URL：

- `index.html` - 所有 URL 引用和 meta 标签
- `sitemap.xml` - 站点地图 URL
- `robots.txt` - Sitemap 路径
- `manifest.json` - 已更新为中文内容

### 修改游戏参数

在 `game.html` 中可以调整以下参数：

- 画布大小：修改 `canvas` 的 `width` 和 `height`
- 五角星大小：修改 `generatePerfectStar` 函数中的半径参数
- 评分阈值：修改 `displayScore` 函数中的分数判断

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License - 详见 LICENSE 文件

## 🌟 致谢

游戏灵感来源于 Neal.fun 的"Draw a Perfect Circle"

---

⭐ 如果你喜欢这个项目，请给它一个 Star！

🎮 开始游戏：[https://yourusername.github.io/](https://yourusername.github.io/)
