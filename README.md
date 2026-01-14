# 张宇 - 个人简历

[![Deploy to GitHub Pages](https://github.com/zy19940510/resume/actions/workflows/deploy.yml/badge.svg)](https://github.com/zy19940510/resume/actions/workflows/deploy.yml)

🌐 **在线访问**: [https://zy19940510.github.io/resume](https://zy19940510.github.io/resume)

## 特性

- 🎨 现代深色主题设计
- 📱 完全响应式布局
- 🖨️ 打印优化（自动切换浅色主题）
- ⚡ 纯静态，无依赖，加载极快
- 🔄 GitHub Actions 自动部署

## 本地预览

```bash
# 方式1: 使用 Python
python -m http.server 3000

# 方式2: 使用 Node.js
npx serve

# 方式3: 直接打开
open index.html
```

## 部署步骤

### 1. 创建 GitHub 仓库

```bash
# 初始化 Git 仓库
cd /Users/ethan/code/resume-site
git init
git add .
git commit -m "Initial commit: Personal resume site"

# 创建远程仓库（需先在 GitHub 创建名为 'resume' 的仓库）
git remote add origin git@github.com:zy19940510/resume.git
git branch -M main
git push -u origin main
```

### 2. 配置 GitHub Pages

1. 进入仓库 **Settings** → **Pages**
2. Source 选择 **GitHub Actions**
3. 等待 Actions 部署完成

### 3. 访问网站

部署完成后访问: `https://zy19940510.github.io/resume`

## 自定义

### 修改内容

直接编辑 `index.html` 中的文本内容

### 修改样式

编辑 `styles.css` 中的 CSS 变量：

```css
:root {
  /* 主色调 */
  --accent-primary: #60a5fa;
  --accent-secondary: #a78bfa;
  
  /* 背景色 */
  --bg-primary: #0a0f1a;
  --bg-card: #1a2234;
}
```

## 技术栈

- HTML5 + CSS3
- Google Fonts (Noto Sans SC + JetBrains Mono)
- Intersection Observer API (滚动动画)
- GitHub Actions (CI/CD)

## License

MIT

