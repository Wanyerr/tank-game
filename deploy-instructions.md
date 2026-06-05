# 部署指南

## 方法一：GitHub Pages（推荐）

### 准备工作
1. 登录 [GitHub.com](https://github.com)
2. 点击右上角 **+** → **New repository**
3. 仓库名任意（如 `tank-game`），设为 **Public**
4. 创建后，进入 **Settings** → **Pages**
5. 在 "Branch" 下拉选择 `main`，文件夹选 `/ (root)`，点击 **Save**

### 上传文件
将项目目录下所有文件上传到 GitHub 仓库：
- `index.html`（主游戏文件）
- `.github/workflows/deploy.yml`（自动部署配置）
- `.codegraph/` 目录无需上传（已在 `.gitignore` 中排除）

### 等待部署
上传后约 1 分钟，GitHub Actions 自动完成部署。
访问 `https://<你的用户名>.github.io/<仓库名>/` 即可开玩。

## 方法二：直接使用

双击打开 `index.html` 即可在浏览器中运行。
