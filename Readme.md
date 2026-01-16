# 聚合资源 - 资源聚合展示平台

一个优雅的资源聚合展示网站，采用法贝尔鸟类插画风格设计，提供开源项目、周刊和精选收藏的统一浏览体验。

## 项目简介

这是一个基于 Deno 的静态网站项目，专注于聚合和展示各类技术资源，包括：
- GitHub 开源项目观察记录
- 设计素材周刊、偷懒爱好者周刊、阮一峰周刊等
- 按编程语言分类的 Star 项目收藏

## 核心功能

### 1. 开源项目观察
- 展示来自 GitHub Issues 的精选开源项目
- 支持 Markdown 内容渲染
- 显示项目元信息（作者、日期、徽章）
- 自动解析和展示项目图片

### 2. 周刊收藏
- 内嵌展示多个技术周刊网站
- 支持 iframe 方式浏览外部内容
- 提供网站控制按钮（刷新、新窗口打开等）

### 3. 精选收藏
- 按编程语言分类展示 Star 项目
- 支持 TypeScript、JavaScript、Python、Rust 等 20+ 种语言
- 卡片式布局，优雅展示项目信息

### 4. 设计特色
- **法贝尔鸟类插画风格**：灵感来自 19 世纪博物学插画
- **复古配色**：羊皮纸色、墨褐色、羽毛蓝等自然色调
- **装饰元素**：卡片四角装饰、花纹分隔线、古典字体
- **响应式设计**：完美适配桌面端和移动端

### 5. 交互功能
- 侧边栏导航，支持锚点跳转
- 移动端汉堡菜单和底部导航
- 图片加载开关（优化性能）
- 平滑滚动和动画效果

## 技术栈

- **运行环境**: Deno
- **前端技术**: 
  - 纯 HTML/CSS/JavaScript
  - Markdown 渲染（markdown-it）
  - 代码高亮（highlight.js）
- **设计风格**: 
  - 自定义 CSS 变量系统
  - Google Fonts（Crimson Text, Cormorant Garamond）
  - SVG 图标和装饰

## 部署说明

### 本地运行
```bash
deno run --allow-net --allow-read main.ts
```

### 部署到 Deno Deploy
点击下方按钮一键部署：

[![Deploy on Deno](https://deno.com/button)](https://app.deno.com/new?clone=https://github.com/denoland/examples&path=hello-world)

## 项目结构

```
.
├── index.html          # 主页面文件（包含所有样式和内容）
├── main.ts            # Deno 服务器入口
├── deno.json          # Deno 配置文件
├── deno.lock          # 依赖锁定文件
└── Readme.md          # 项目说明文档
```

## 特色亮点

1. **单文件架构**: 所有样式和内容集成在一个 HTML 文件中，便于维护和部署
2. **性能优化**: 
   - 图片懒加载选项
   - CSS 动画优化
   - 响应式图片处理
3. **用户体验**:
   - 移动端友好的触摸交互
   - 平滑的页面滚动
   - 直观的导航系统
4. **内容丰富**: 
   - 支持 Markdown 格式内容
   - 代码语法高亮
   - 多媒体内容展示

## 浏览器兼容性

- Chrome/Edge (推荐)
- Firefox
- Safari
- 移动端浏览器

## 许可证

本项目遵循原 Deno Examples 项目的许可证。

## 贡献

欢迎提交 Issue 和 Pull Request！