# 冯圣杰个人主页 GitHub Pages 发布说明

这个目录已经是 GitHub Pages 可直接使用的最终发布包。

## 目录内容

- `index.html`：网站首页
- `portrait.jpg`：个人头像
- `resume-retail.pdf`：PDF 简历
- `resume.docx`：Word 简历
- `.nojekyll`：避免 GitHub Pages 用 Jekyll 处理静态资源

## 推荐发布方式

最推荐的方式是创建一个仓库，仓库名直接用：

`你的 GitHub 用户名.github.io`

这样发布后，网站地址最简洁：

`https://你的用户名.github.io`

## 逐步操作

### 第 1 步：登录 GitHub

打开：

`https://github.com`

登录你的 GitHub 账号。

### 第 2 步：创建仓库

登录后依次点击：

1. 右上角头像左边的 `+`
2. 点击 `New repository`

然后填写：

- `Repository name`：`你的用户名.github.io`
- `Description`：可以写 `Personal homepage`
- `Public`：选择公开

接着点击：

`Create repository`

### 第 3 步：上传网站文件

进入新仓库后，点击：

1. `Add file`
2. `Upload files`

把这个目录里的所有文件拖进去：

- `index.html`
- `portrait.jpg`
- `resume-retail.pdf`
- `resume.docx`
- `.nojekyll`

页面下方会看到提交区域。

在 `Commit changes` 里可以写：

- 标题：`Initial homepage publish`

然后点击：

`Commit changes`

### 第 4 步：打开 GitHub Pages

回到仓库首页后，依次点击：

1. `Settings`
2. 左侧菜单找到 `Pages`

在 `Build and deployment` 里设置：

- `Source`：`Deploy from a branch`
- `Branch`：`main`
- `Folder`：`/ (root)`

然后点击：

`Save`

### 第 5 步：等待发布

保存之后，GitHub 会开始部署。

通常几分钟内完成。

你可以：

1. 刷新 `Pages` 页面
2. 看到顶部出现绿色或蓝色提示
3. 页面会显示你的网站地址

地址一般就是：

`https://你的用户名.github.io`

### 第 6 步：打开网站

点击那个网址，就能在互联网上访问你的主页。

## 后续更新网站

以后你只要更新内容，再重复上传新文件即可：

1. 进入仓库首页
2. 点击 `Add file`
3. 点击 `Upload files`
4. 上传覆盖旧文件
5. 点击 `Commit changes`

GitHub Pages 会自动重新部署。

## 如果你不想用用户名仓库名

也可以创建普通仓库，比如：

`personal-homepage`

这种情况下，网址通常会变成：

`https://你的用户名.github.io/personal-homepage/`

但第一次上线不建议这么做，因为不如用户名站点简洁。

## 建议

第一次上线就用：

`你的用户名.github.io`

这是最省事、最像正式个人主页的做法。
