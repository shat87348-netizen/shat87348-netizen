# GitHub 主页设置指南

## 📋 目录
1. [什么是 GitHub 主页](#什么是-github-主页)
2. [如何设置](#如何设置)
3. [自定义说明](#自定义说明)
4. [高级功能](#高级功能)
5. [常见问题](#常见问题)

---

## 什么是 GitHub 主页

GitHub 主页（Profile README）是一个特殊的仓库，可以让你的 GitHub 个人资料页面更加个性化和专业。当你创建一个与你的 GitHub 用户名同名的仓库时，README.md 文件的内容会自动显示在你的个人资料页面上。

---

## 如何设置

### 步骤 1：创建仓库
1. 登录 GitHub
2. 点击右上角的 "+" 号，选择 "New repository"
3. **重要：** 仓库名必须与你的 GitHub 用户名完全一致（区分大小写）
4. 设置为 **Public**（必须是公开的）
5. 勾选 "Add a README file"
6. 点击 "Create repository"

### 步骤 2：编辑 README.md
1. 克隆或下载本仓库的 `README.md` 文件
2. 将所有 `你的用户名` 替换为你的实际 GitHub 用户名
3. 将所有 `你的名字` 替换为你的真实姓名或昵称
4. 自定义其他内容（技能、项目、联系方式等）

### 步骤 3：提交更改
1. 将修改后的 README.md 推送到你的 GitHub 主页仓库
2. 刷新你的 GitHub 个人资料页面
3. 你的新主页就会显示出来了！

---

## 自定义说明

### 1. 个人信息部分
```markdown
### 🚀 全栈开发者 | 技术爱好者 | 开源贡献者
```
- 修改你的职业描述和标签
- 可以添加更多表情符号和描述

### 2. GitHub 统计卡片
这些统计卡片会自动从你的 GitHub 账户获取数据：
- **GitHub Stats**: 显示你的贡献统计、仓库数量等
- **GitHub Streak**: 显示你的连续贡献天数
- **Top Languages**: 显示你最常用的编程语言

**自定义主题：**
- 将 `theme=radical` 改为其他主题，如：`dark`, `vue`, `tokyonight`, `onedark` 等
- 访问 [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) 查看更多主题

### 3. 技术栈徽章
```markdown
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
```
- 添加或删除你熟悉的技术
- 访问 [Shields.io](https://shields.io/) 创建自定义徽章
- 访问 [Simple Icons](https://simpleicons.org/) 查找更多 logo

### 4. 项目展示
在"精选项目"部分：
- 替换项目名称和描述
- 更新技术栈标签
- 添加项目链接（GitHub 仓库链接）

### 5. 联系方式
```markdown
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/你的用户名)
```
- 更新所有社交媒体的链接
- 添加或删除不需要的平台
- 确保链接正确

---

## 高级功能

### 1. 添加动态内容

#### GitHub 活动图
```markdown
![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=你的用户名&theme=redical)
```
- 自动显示你的 GitHub 活动热力图
- 可以自定义主题和颜色

#### GitHub 成就徽章
```markdown
![GitHub Trophy](https://github-profile-trophy.vercel.app/?username=你的用户名&theme=radical)
```
- 显示你的 GitHub 成就（如 Star、Fork、Commit 等）

### 2. 添加访客计数器
```markdown
![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=你的用户名.你的用户名)
```
- 统计访问你主页的人数

### 3. 添加技能进度条
你可以使用 HTML 和 CSS 创建技能进度条：
```html
<div align="center">
  
  <img src="https://img.shields.io/badge/JavaScript-90%25-yellow" />
  <img src="https://img.shields.io/badge/Python-85%25-blue" />
  <img src="https://img.shields.io/badge/React-80%25-lightblue" />
  
</div>
```

### 4. 添加动画效果
使用 GitHub Actions 可以创建动态更新的内容，比如：
- 自动更新的博客文章列表
- 实时更新的 Spotify 播放状态
- 自动生成的 LeetCode 解题统计

---

## 常见问题

### Q: 为什么我的主页没有显示？
A: 检查以下几点：
- 仓库名是否与用户名完全一致（区分大小写）
- 仓库是否为 Public
- README.md 文件是否在仓库根目录
- 等待几分钟让 GitHub 更新缓存

### Q: 如何更新统计信息？
A: GitHub 统计卡片会自动更新，但可能需要一些时间。你可以：
- 清除浏览器缓存
- 等待 GitHub API 更新（通常几分钟到几小时）

### Q: 可以使用 HTML 吗？
A: GitHub README 支持部分 HTML，但为了兼容性，建议主要使用 Markdown。

### Q: 如何添加更多表情符号？
A: 访问 [Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/) 或使用系统表情符号。

### Q: 统计卡片不显示怎么办？
A: 可能的原因：
- API 请求限制（等待一段时间）
- 用户名拼写错误
- 网络问题

---

## 有用的资源

- [GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/) - 在线生成器
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme) - 优秀示例集合
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) - 统计卡片文档
- [Shields.io](https://shields.io/) - 徽章生成器
- [Simple Icons](https://simpleicons.org/) - 图标库

---

## 下一步

1. ✅ 完成基本设置
2. 🎨 自定义样式和内容
3. 📊 添加更多统计和动态内容
4. 🚀 分享你的主页！

祝你创建一个漂亮的 GitHub 主页！🎉

