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

## 两页投递版（2026-11）

打开 `resume-print.html`，使用浏览器打印，选择 A4、保存为 PDF、开启背景图形并关闭页眉页脚。页面自带两页分页样式。

已按本人 2026-11-01 确认更新工作起止月份、项目职责、当前阶段与指标口径。

- `index.html`：完整在线简历；`resume-print.html`：两页阅读 / 打印版；`resume.pdf`：对应 PDF 下载。
- `resume-facts.json`：本次本人确认的事实记录，不含求职薪资偏好。
- NiceAPI 独立二次开发、部署与运营，线上运行，按日统计、每日重置，日均处理 50 亿 Token、每日 20+ 调用用户。
- DeskClaw 主导、停止维护；Workflow OS 独立完成、Demo 完成未上线；AI InkLoop 主导、暂停；Browser Pilot 参与、封版停止迭代。
- F1API 单接口联调排期平均约 3 小时 → 半小时以内；50+ 团队为深度使用团队；500+ 为路由表总路由数。

推送 `main` 后由现有 GitHub Actions 发布到原 GitHub Pages 地址。
