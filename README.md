# Tag before Dawn - 游戏着陆页

这是"Tag before Dawn"VR社交推理游戏的官方着陆页项目。

## 项目概述

Tag before Dawn是一款沉浸式VR社交推理游戏，玩家在温馨的木屋中体验紧张刺激的角色扮演冒险。这个着陆页展示了游戏特色、截图，并提供社交媒体链接。

## 功能特性

- 🎮 游戏展示和介绍
- 🖼️ 游戏截图展示
- 🔗 社交媒体链接（Discord、YouTube、TikTok、Quest商店）
- 📱 完全响应式设计
- 🎨 现代化UI设计
- ⚡ 优化的性能和动画效果
- 📄 隐私政策页面

## 文件结构

```
GTLandingPageTemp/
├── index.html          # 主页面
├── privacy.html        # 隐私政策页面
├── styles.css          # 样式文件
├── script.js           # JavaScript功能
├── img/                # 图片资源目录
│   └── vlcsnap-2025-09-03-11h31m02s087.png
└── README.md           # 项目说明文档
```

## 部署到GitHub Pages

### 方法1：自动部署（推荐）

1. 在GitHub上创建新的仓库
2. 将项目文件上传到仓库
3. 进入仓库设置（Settings）
4. 找到"Pages"选项
5. 在"Source"中选择"Deploy from a branch"
6. 选择"main"分支和"/ (root)"文件夹
7. 点击"Save"

### 方法2：手动部署

1. 克隆仓库到本地
2. 确保所有文件都在根目录
3. 推送到GitHub
4. 按照方法1的步骤3-7操作

## 自定义配置

### 更新社交媒体链接

在`index.html`文件中找到社交媒体按钮部分，更新以下链接：

```html
<!-- Discord -->
<a href="https://discord.gg/your-discord" class="social-btn discord">

<!-- YouTube -->
<a href="https://www.youtube.com/@your-channel" class="social-btn youtube">

<!-- TikTok -->
<a href="https://www.tiktok.com/@your-account" class="social-btn tiktok">

<!-- Quest商店 -->
<a href="https://www.meta.com/experiences/your-app" class="social-btn quest">
```

### 更新游戏截图

将新的游戏截图放在`img/`目录中，并在`index.html`中更新图片路径：

```html
<img src="img/your-new-screenshot.png" alt="游戏截图描述" class="game-screenshot">
```

### 修改颜色主题

在`styles.css`文件中，可以修改以下CSS变量来改变主题色彩：

```css
/* 主色调 */
--primary-color: #3498db;
--secondary-color: #2c3e50;

/* 渐变背景 */
.hero {
    background: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);
}
```

## 技术栈

- **HTML5**: 语义化标记
- **CSS3**: 现代CSS特性，包括Grid、Flexbox、动画
- **JavaScript (ES6+)**: 交互功能和动画
- **响应式设计**: 支持所有设备尺寸
- **性能优化**: 图片懒加载、CSS动画优化

## 浏览器支持

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- 移动端浏览器

## 性能优化

- 图片懒加载
- CSS动画优化
- 字体预加载
- 响应式图片
- 最小化重绘和重排

## 本地开发

1. 克隆项目到本地
2. 使用本地服务器运行（避免CORS问题）
3. 推荐使用Live Server（VS Code扩展）或Python简单服务器

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js
npx serve .
```

## 更新日志

### v1.0.0 (2024-12-19)
- 初始版本发布
- 完整的着陆页功能
- 响应式设计
- 隐私政策页面
- 社交媒体集成

## 贡献

欢迎提交Issue和Pull Request来改进这个项目。

## 许可证

本项目采用MIT许可证。

## 联系方式

如有问题或建议，请通过以下方式联系：

- Discord: 通过我们的Discord服务器
- 邮箱: privacy@beforedawn.com

---

**注意**: 部署前请确保更新所有社交媒体链接和联系信息为您的实际链接。
