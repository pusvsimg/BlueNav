# WebNav Hub

WebNav Hub 是一个现代化的网址导航网站，提供清晰的分类和优雅的用户界面。它采用响应式设计，支持深色模式，并提供流畅的用户体验。

## 特性

### 多类别导航 🎯

- AI搜索工具
- 社交媒体平台
- 实用工具
- 科技资讯
- 开发者资源
- 云存储服务
- 电子邮件服务

### 现代化设计 🎨

- 响应式布局
- 深色模式支持
- 平滑滚动效果
- 优雅的动画过渡
- Font Awesome 图标支持

### 技术特点 🚀

- 纯静态网站实现
- 无需后端服务支持
- 快速加载性能
- 全平台兼容支持

## 部署指南

### 通过 GitHub Pages 部署

1. Fork 本仓库
2. 进入仓库设置（Settings）
3. 找到 Pages 设置选项
4. 在 Source 中选择 `main` 分支
5. 保存后等待部署完成

### 通过 Cloudflare Pages 部署

1. 在 Cloudflare Dashboard 中选择 Pages
2. 点击 "Create a project"
3. 连接你的 GitHub 账户并选择本仓库
4. 配置部署设置：
   - 构建命令：留空（无需构建）
   - 构建输出目录：留空（使用根目录）
5. 点击部署按钮

## 本地开发

1. 克隆仓库：

```bash
git clone https://github.com/yourusername/webnav-hub.git
```

2. 使用本地服务器运行（以 Python 为例）：

```bash
# Python 3
python -m http.server 8000
```

3. 在浏览器中访问 `http://localhost:8000`

## 自定义指南

### 添加新链接

在 `w.html` 文件中找到相应的分类部分，按照以下格式添加新的链接卡片：

```html
<div class="link-card">
  <i class="fa-solid fa-icon-name"></i>
  <h3>网站名称</h3>
  <a href="https://website-url" target="_blank" rel="noopener noreferrer">
    <span class="sr-only">Visit Website Name</span>
  </a>
</div>
```

### 修改样式

样式定义在 `<style>` 标签中，你可以根据需要修改：

- 主题颜色：修改 `:root` 中的变量
- 卡片样式：修改 `.link-card` 相关样式
- 响应式布局：修改媒体查询规则

## 贡献指南

欢迎提交 Pull Requests 来改进这个项目。你可以：

- 添加新的实用链接
- 改进用户界面设计
- 优化代码性能表现
- 修复已知问题或错误

## 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

## 致谢

- [Font Awesome](https://fontawesome.com/) - 提供图标支持
- 所有项目贡献者和用户

---

🌟 如果这个项目对你有帮助，欢迎给它一个星标！