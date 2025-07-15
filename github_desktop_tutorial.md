# GitHub Desktop 新手完整教程

## 什么是 GitHub？

GitHub 是一个代码托管平台，可以让你：
- 保存和备份你的代码
- 与他人协作开发项目
- 查看代码的修改历史
- 分享你的项目给全世界

## 1. 注册 GitHub 账号

1. 前往 [GitHub 官网](https://github.com/signup) 注册账号
2. 使用你的邮箱注册（QQ邮箱、Gmail、Outlook都行，平常使用的就可以）
3. 记住你的用户名和密码

## 2. 下载 GitHub Desktop

1. 前往 [GitHub Desktop 官网](https://desktop.github.com/) 下载
2. 如果官网下载太慢，可以在电脑平台应用商店搜索"GitHub Desktop"
3. 下载完成后安装并打开

## 3. 登录你的 GitHub 账号

1. 第一次打开软件会提示登录
2. 输入你的用户名和密码
3. 按照提示完成登录

## 4. 创建你的第一个仓库

### 方法一：在网页端创建（推荐）

1. 登录 GitHub 网站
2. 点击右上角的"+"号，选择"New repository"
3. 填写仓库信息：
   - **Repository name**：仓库名称（如：my-first-project）
   - **Description**：项目描述（可选）
   - 选择 **Public**（公开）或 **Private**（私有）
   - 选择是否"Add a README file"
4. 点击"Create repository"

### 方法二：在 GitHub Desktop 中创建

1. 打开 GitHub Desktop
2. 点击左上角的"Create new repository"
3. 填写仓库信息并选择本地路径
4. 点击"Create repository"

## 5. 克隆仓库到本地

1. 在 GitHub 网页端，进入目标仓库
2. 点击绿色的"Code"按钮
3. 选择"Open with GitHub Desktop"
4. 选择本地存储路径（建议选择你熟悉的文件夹）
5. 点击"Clone"

## 6. 编写和修改代码

1. 点击 Desktop 中的"Show in Explorer"（Windows）或"Show in Finder"（Mac）打开项目文件夹
2. 在文件夹中创建或编辑你的文件
3. 保存文件后，回到 GitHub Desktop

## 7. 提交你的更改

### 理解提交（Commit）
- 提交就像是给你的项目拍快照
- 每次提交都会记录你做了什么改动
- 提交信息要简洁明了地描述你的更改

### 提交步骤

1. 在 GitHub Desktop 中，你会看到所有的更改
2. 在左下角的提交区域：
   - **Summary**：简短描述你的更改（必填）
   - **Description**：详细描述（可选）
3. 点击"Commit to main"

**提交描述示例：**
- "添加了登录功能"
- "修复了页面显示错误"
- "更新了项目说明文档"

## 8. 推送到 GitHub

1. 提交后，点击右上角的"Push origin"或"Publish branch"
2. 这样你的更改就上传到 GitHub 了
3. 其他人就可以看到你的最新代码

## 9. 多人协作

### 邀请协作者

1. 在 GitHub 网页端进入你的仓库
2. 点击"Settings"标签
3. 左侧点击"Collaborators"
4. 点击"Add people"
5. 输入对方的 GitHub 用户名或邮箱
6. 发送邀请

### 协作者如何加入

1. 接受邀请邮件
2. 使用 GitHub Desktop 克隆仓库
3. 开始协作开发

### 处理冲突

当多人修改同一文件时可能出现冲突：
1. GitHub Desktop 会提示有冲突
2. 点击冲突的文件
3. 手动选择保留哪些更改
4. 重新提交

## 10. 常用操作

### 拉取最新代码
- 点击"Fetch origin"检查更新
- 如果有更新，点击"Pull origin"获取最新代码

### 查看历史
- 点击"History"标签查看所有提交记录
- 点击任意提交可以看到具体的更改

### 切换分支
- 点击"Current branch"可以切换或创建分支
- 分支就像是代码的不同版本

## 11. 常见问题解答

### Q: 我不小心删除了文件怎么办？
A: 在 GitHub Desktop 中可以看到删除记录，可以撤销这个更改。

### Q: 如何撤销提交？
A: 在 History 中找到要撤销的提交，右键选择"Revert"。

### Q: 推送失败了怎么办？
A: 通常是因为远程仓库有新的更改，先点击"Pull origin"拉取最新代码。

### Q: 如何下载别人的项目？
A: 在 GitHub 网页端点击"Code" → "Open with GitHub Desktop"即可克隆。

## 12. 一些建议

1. **经常提交**：不要等到写完很多代码才提交
2. **写清楚的提交信息**：让别人（和未来的你）能看懂你这次提交做了什么
3. **及时拉取**：开始工作前先拉取最新代码
4. **备份重要项目**：GitHub 就是你的云端备份

开始你的 GitHub 之旅吧！记住，熟能生巧，一开始可能觉得生疏，当你在一个项目中磨练一段不长的时间后，你会发现你已经掌握了这项技能。

---

**需要帮助？**
- [GitHub Desktop 官方文档](https://docs.github.com/en/desktop)
- [GitHub 帮助中心](https://support.github.com/)
- 遇到问题可以在 GitHub 社区提问或询问作者

## 版权声明

本教程由 Azuredusk026(https://github.com/Azuredusk026) 编写，欢迎转载和分享，请保留原作者信息。

## 更新日志

- 2025-07-14：创建初始版本
- 待更新：根据用户反馈持续改进
