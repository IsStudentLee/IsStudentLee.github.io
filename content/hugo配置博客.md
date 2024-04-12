# 1 安装hugo 

## 1.1 mac 

​	brew install hugo

## 1.2 windows

### 1.2.1 github下载安装

​	[Releases · gohugoio/hugo (github.com)](https://github.com/gohugoio/hugo/releases)

### 1.2.2 环境变量配置

​	path: “D:\software\hugo_0.124.1_windows-amd64\ ”  这个路径不需要精确到`hugo.exe`

# 2 用hugo生成博客

​	hugo new site "博客名"

## 2.1 下载并设置主题

​	“[Complete List | Hugo Themes (gohugo.io)](https://themes.gohugo.io/)”

# 3 本地启动博客

​	hugo server -t "主题名" --buildDrafts

## 3.1 写一篇文章

​	hugo new post/blog.md

# 4 将博客部署到远端服务器

​	github: 新建仓库名必须昵称+.github.io

​	hugo --theme="主题名" --baseUrl="https://isstudentlee.github.io/" --buildDrafts