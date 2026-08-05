# 张宇 - 个人简历

[![Deploy to GitHub Pages](https://github.com/zy19940510/resume/actions/workflows/deploy.yml/badge.svg)](https://github.com/zy19940510/resume/actions/workflows/deploy.yml)

🌐 **在线访问**: [https://zy19940510.github.io/resume](https://zy19940510.github.io/resume)

## 特性

- 🍎 苹果风格的克制浅色设计
- 🧭 围绕 AI 原生研发、复杂系统、端云协同与商业交付重组内容
- 📱 完全响应式布局
- ♿ 语义化结构、键盘焦点与减少动效支持
- 🖨️ 打印优化
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
  --paper: #f5f5f7;
  --ink: #1d1d1f;
  --blue: #0071e3;
  --dark: #101012;
}
```

## 技术栈

- HTML5 + CSS3
- 系统字体栈（SF Pro / 苹方优先）
- Intersection Observer API (滚动动画)
- GitHub Actions (CI/CD)

## License

MIT
