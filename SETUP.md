# 怎么把这些文件变成 GitHub 仓库

> 给不会用 GitHub 的种灯人。10 分钟搞定。

---

## 第一次使用 GitHub？

### 1. 注册账号

打开 [github.com](https://github.com)，点 Sign up。
- 用一个你愿意公开的用户名（这会出现在你的仓库地址里）
- 邮箱要能收到验证码
- 选 Free 版本

### 2. 安装 GitHub Desktop（推荐给非程序员）

直接用网页或命令行也行，但 GitHub Desktop 最直观。

下载：[desktop.github.com](https://desktop.github.com/)

装好后用第 1 步的账号登录。

---

## 创建你的 Lantern 仓库

### 3. 在 GitHub 网站建空仓库

1. 登录 github.com
2. 右上角 `+` → New repository
3. 填写：
   - **Repository name**: `lantern`（小写）
   - **Description**: `一盏你为自己点的灯 · 个人成长笔记本`
   - **Public**（公开）
   - **不要**勾选 "Add a README file"（我们自己上传）
   - **不要**勾选 .gitignore 和 license（我们自己上传）
4. 点 Create repository

### 4. 把我给你的文件传上去

**最简单的方法（网页拖拽）**：

1. 在你的新仓库页面，点 "uploading an existing file" 链接
2. 把我给你的整个 `lantern` 文件夹里的文件全部拖进去：
   - `README.md`
   - `MANIFESTO.md`
   - `ROADMAP.md`
   - `ARCHITECTURE.md`
   - `LICENSE`
   - `blog/blog-01-why-lantern.md`
3. 拖完之后，下方会有个 "Commit changes" 按钮，描述写 `Initial commit · 种下一盏灯`
4. 点击提交

### 5. 把现有 HTML 原型也加进去

1. 在仓库页面点 "Add file" → "Upload files"
2. 上传我之前给你的 `commonplace.html` 文件
3. 但放到一个新文件夹里——上传时把它命名为 `prototypes/v0.1-commonplace.html`
   （在文件名前直接输入 `prototypes/` 就会自动建文件夹）
4. 提交

---

## 让 HTML 原型变成可访问的网站

### 6. 启用 GitHub Pages

1. 仓库页面 → Settings → Pages（左侧菜单）
2. Source 选 `Deploy from a branch`
3. Branch 选 `main`，文件夹选 `/ (root)`
4. 保存

几分钟后，你的网站会在这里上线：
```
https://你的用户名.github.io/lantern/
```

要直接访问原型，URL 是：
```
https://你的用户名.github.io/lantern/prototypes/v0.1-commonplace.html
```

**回头把这个链接更新到 README.md 里**——找到 "试试 v0.1" 那行，把链接换成上面的真实地址。

---

## 修改 README 里的占位符

我在文档里留了几个地方需要你填上自己的信息：

1. `README.md` 里的 `[👉 试试 v0.1](./prototypes/v0.1-commonplace.html)` → 换成上面的真实链接
2. `blog/blog-01-why-lantern.md` 里的 `[github.com/你的用户名/lantern]` → 换成你的真实仓库地址
3. 任何你觉得需要改的地方——这是**你的项目**，文档只是起点

---

## 发布第一篇博客

你有几个选项：

**选项 A · 最简单**：博客就放在 GitHub 仓库的 `blog/` 文件夹。任何人通过仓库都能看到。
- 优点：零成本、零配置
- 缺点：没有阅读体验

**选项 B · 推荐**：用免费博客平台
- [少数派](https://sspai.com) · 中文创作社区，质量高
- [Medium](https://medium.com) · 英文也有中文区
- [即刻](https://web.okjike.com) · 短内容也合适
- 把博客复制粘贴过去发出来，然后把链接更新到 README

**选项 C · 进阶**：用 GitHub Pages + Jekyll 做自己的博客网站。这个需要多一些配置，等你想做的时候再说。

---

## 第一次发出去的"仪式"

发出博客的那一刻，建议做这些事：

1. **告诉一个具体的人**：不是发到群里，是私聊一个你尊重的朋友，"我做了这个，想听你的反馈"
2. **写一条社交媒体**：不长，三句话——"我是谁、我做了什么、欢迎围观"
3. **截图存档**：保留你发出去的第一天的状态。3 个月后再回看，你会感谢自己。
4. **找守灯人庆祝**：现在还没做出来代理，所以暂时由你自己庆祝——倒杯酒，听首歌，记住这一刻。

---

## 如果卡住了

完全正常。建议：

- GitHub 注册卡住 → 国内有时网络不稳，挂个梯子或换时间试
- 上传文件卡住 → 一次少传几个
- 不知道怎么写第一条社交媒体 → 直接拿 `blog-01` 的第一段贴上去也行
- 觉得"做这个有什么用啊" → 这就是点灯人该上场的时刻了。现在还没做出来，先去散个步，明天继续

---

## 一个小提醒

很多人卡在"我还没准备好发出去"。

如果你也这样想，重读一下 ROADMAP 里的话：**70 分就发出去**。

仓库里少一篇博客不重要，README 写得不完美不重要，原型有 bug 不重要。

重要的是：**今天有一束光被点亮了，被世界看见了**。

剩下的，慢慢来。

---

*Welcome aboard, 种灯人.*
