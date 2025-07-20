# 🧰 GitHub 仓库管理工具

> 一个轻量级的 GitHub 仓库管理工具，支持登录、浏览、上传、下载、删除等操作，并提供 GitHub Pages 托管、GitHub Actions 触发等高级功能。

<p align="center">
  <!-- 创建日期 --><img alt="GitHub Created At" src="https://img.shields.io/github/created-at/xyz66882/GitHub-repository?logo=github&label=%E5%88%9B%E5%BB%BA%E6%97%A5%E6%9C%9F">
  <!-- 下载量 --><a href="https://github.com/xyz66882/GitHub-repository/releases"><img src="https://img.shields.io/github/downloads/xyz66882/GitHub-repository/total?logo=github&label=%E4%B8%8B%E8%BD%BD%E9%87%8F"></a>
  <!-- 贡献者 --><a href="https://github.com/xyz66882/GitHub-repository/graphs/contributors"><img src="https://img.shields.io/github/contributors-anon/xyz66882/GitHub-repository?logo=github&label=%E8%B4%A1%E7%8C%AE%E8%80%85"></a>
  <!-- 最新版本 --><a href="https://github.com/xyz66882/GitHub-repository/releases/"><img src="https://img.shields.io/github/release/xyz66882/GitHub-repository?logo=github&label=%E6%9C%80%E6%96%B0%E7%89%88%E6%AC%A1"></a>
  <!-- 问题数 --><a href="https://github.com/xyz66882/GitHub-repository/issues"><img src="https://img.shields.io/github/issues-raw/xyz66882/GitHub-repository?logo=github&label=%E9%97%AE%E9%A2%98"></a>
  <!-- 讨论数 --><a href="https://github.com/xyz66882/GitHub-repository/discussions"><img src="https://img.shields.io/github/discussions/xyz66882/GitHub-repository?logo=github&label=%E8%AE%A8%E8%AE%BA"></a>
  <!-- 仓库大小 --><a href="https://github.com/xyz66882/GitHub-repository"><img src="https://img.shields.io/github/repo-size/xyz66882/GitHub-repository?logo=github&label=%E4%BB%93%E5%BA%93%E5%A4%A7%E5%B0%8F"></a>
</p>

---

## 📋 功能列表

### 🔐 1. 用户认证
- GitHub Token 登录
- Token 本地存储（自动登录）
- 用户菜单（显示用户名 / 退出）

### 🗂 2. 仓库管理
- 查看仓库列表
- 创建新仓库（名称 / 描述 / 私有设置）
- 复刻仓库（通过 URL）
- 删除仓库

### 📁 3. 文件操作
- 浏览仓库目录结构（面包屑导航）
- 创建文件夹
- 上传文件（支持多文件）
- 下载文件（支持单个 / 批量下载为 ZIP）
- 删除文件 / 文件夹（支持单个 / 批量）
- 重命名文件
- 文件类型图标识别

### ⚙️ 4. 高级功能
- 静态网站托管（GitHub Pages 配置）
- 运行工作流（触发 GitHub Actions 工作流）
- 工作流进度监控
- CDN 链接生成（使用 jsDelivr 代理）

### 🧭 5. 其他实用功能
- 返回上级目录
- 刷新当前目录
- 仓库根目录快捷访问
- 路径递归快捷访问

---

## 🖼️ 效果图预览

<div align="center">
  <p><strong>未登录界面（电脑端）</strong></p>
  <img style="max-width:100%; height:auto;" src="https://github.com/user-attachments/assets/005d5f4f-f985-49a2-9992-39298da73ed8" alt="电脑未登录" />

  <p><strong>已登录界面（电脑端）</strong></p>
  <img style="max-width:100%; height:auto;" src="https://github.com/user-attachments/assets/89f7d150-cd39-41e6-970e-a13d96986999" alt="电脑界面" />

  <p><strong>移动端界面</strong></p>
  <div style="display: flex; justify-content: center; gap: 15px; overflow-x: auto;">
    <img style="width: 500px; height: auto;" src="https://github.com/user-attachments/assets/a8e1ef93-bf20-465b-80c5-0c42a31de31c" alt="手机界面" />
    <img style="width: 450px; height: auto;" src="https://github.com/user-attachments/assets/6772d950-9e81-4602-93e5-ea5af5e59a58" alt="手机壁纸设置" />
  </div>
</div>

---

## 🛠 技术实现

本工具完全基于 **GitHub API** 实现所有功能，结合前端二改美化，提供简洁直观的操作界面，适合开发者进行 GitHub 仓库的快速管理。
