# PiPiClaw.Team.Web - 皮皮虾公司官网

[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)](https://github.com/anan1213095357/PiPiClaw.Team.Web)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success)]()

## 📖 项目简介

皮皮虾公司官网是皮皮虾前端开发公司的官方展示网站，采用纯前端技术栈构建，无需后端服务器支持，可直接部署到任何静态托管平台。

## 🚀 快速开始

### 本地预览

```bash
# 方法 1: 直接双击打开 HTML 文件
pipiclaw-company-website.html

# 方法 2: 使用 Python 启动本地服务器
python -m http.server 8080
# 访问 http://localhost:8080/pipiclaw-company-website.html

# 方法 3: 使用 Node.js http-server
npx http-server -p 8080
```

### 在线访问

访问 GitHub Pages 或部署后的生产环境 URL。

## 📁 项目结构

```
PiPiClaw.Team.Web/
├── README.md                          # 项目说明文档
├── .gitignore                         # Git 忽略配置
├── pipiclaw-company-website.html      # 主 HTML 文件（包含内联 CSS 和 JS）
└── pipiclaw-company-website.md        # 详细技术文档
```

## 🛠 技术栈

| 技术 | 说明 |
|------|------|
| HTML5 | 语义化标签构建页面结构 |
| CSS3 | 原生 CSS，包含变量、Flexbox、Grid、动画 |
| JavaScript | ES6+，用于交互逻辑和移动端菜单控制 |

### 核心特性

- ✅ 响应式设计（桌面/平板/手机全适配）
- ✅ CSS 变量主题系统
- ✅ 纯静态，零依赖
- ✅ 单文件架构，部署简单
- ✅ 移动端汉堡菜单
- ✅ 平滑滚动锚点导航

## 📦 部署指南

### GitHub Pages

1. 进入仓库 Settings → Pages
2. 选择部署分支（main）和文件夹（/root）
3. 保存后等待部署完成
4. 访问 `https://anan1213095357.github.io/PiPiClaw.Team.Web/`

### Vercel

1. 登录 [Vercel](https://vercel.com)
2. 导入此 GitHub 仓库
3. 自动部署完成

### Netlify

1. 登录 [Netlify](https://netlify.com)
2. 连接 GitHub 仓库
3. 构建设置：无需构建命令，发布目录为 `/`

### 其他平台

- 阿里云 OSS
- 腾讯云 COS
- Cloudflare Pages
- Firebase Hosting

## 📝 功能模块

| 模块 | 描述 |
|------|------|
| 导航栏 | 固定定位，含 Logo 和导航链接，移动端汉堡菜单 |
| Hero 区域 | 首屏核心展示，渐变背景，CTA 按钮 |
| 公司简介 | 使命愿景、核心优势、数据统计 |
| 组织架构 | 五大核心团队展示卡片 |
| 对接流程 | 6 步标准化项目对接流程 |
| 协作规范 | 6 大工作标准说明 |
| 联系方式 | 地址、邮箱、电话、工作时间 |
| 页脚 | 版权信息和备案号 |

## 🔧 开发指南

### 修改内容

1. 使用 VS Code 或其他编辑器打开 `pipiclaw-company-website.html`
2. 搜索需要修改的内容
3. 保存后刷新浏览器查看效果

### 主题定制

在 HTML 文件的 `<style>` 标签中修改 CSS 变量：

```css
:root {
    --primary-color: #2563eb;      /* 主色调 */
    --secondary-color: #64748b;    /* 辅助色 */
    --accent-color: #0ea5e9;       /* 强调色 */
}
```

### 添加新模块

```html
<section class="new-section" id="new-section">
    <h2>新模块标题</h2>
    <p>模块内容...</p>
</section>
```

## 📱 浏览器兼容性

| 浏览器 | 最低版本 | 状态 |
|--------|----------|------|
| Chrome | 80+ | ✅ |
| Edge | 80+ | ✅ |
| Firefox | 75+ | ✅ |
| Safari | 13+ | ✅ |

## 📄 许可证

MIT License

## 👥 团队

- **技术文档**: 杨紫萱
- **DevOps**: 韩文博
- **联系邮箱**: support@pipiclaw.com

## 📞 联系方式

- 📧 business@pipiclaw.com
- 📞 400-888-6666
- 🏢 北京市海淀区中关村科技园

---

*最后更新：2026 年 3 月 28 日*
