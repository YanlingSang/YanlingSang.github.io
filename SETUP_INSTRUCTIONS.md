# 网站设置说明

## ✅ 已完成的更新

所有内容已经更新完成：
- ✓ 个人信息和联系方式
- ✓ 个人照片
- ✓ 简历PDF
- ✓ 主页内容
- ✓ CV页面
- ✓ 所有出版物信息

## 🚀 推送到GitHub并在线预览

### 方法1：使用GitHub Desktop（推荐）
1. 打开GitHub Desktop
2. 选择这个repository
3. 查看所有更改
4. 写一个commit message，例如："Update personal information and publications"
5. 点击"Commit to main"
6. 点击"Push origin"
7. 等待几分钟后访问：https://yanlingsang.github.io

### 方法2：使用命令行
```bash
cd /Users/sylvia/Desktop/26fall/YanlingSang.github.io
git add .
git commit -m "Update personal information and publications"
git push origin main
```

然后访问 https://yanlingsang.github.io 查看你的网站！

## 🔧 本地预览（可选，稍后配置）

如果你需要本地预览功能，可以选择以下方案：

### 方案A：安装Docker（推荐用于本地开发）
1. 从 https://www.docker.com/products/docker-desktop 下载Docker Desktop
2. 安装后运行：
```bash
cd /Users/sylvia/Desktop/26fall/YanlingSang.github.io
docker build -t jekyll-site .
docker run -p 4000:4000 --rm -v $(pwd):/usr/src/app jekyll-site
```
3. 访问 http://localhost:4000

### 方案B：完成Ruby 3.2.2安装
1. 等待之前的Ruby安装完成（大约5-10分钟）
2. 运行：
```bash
eval "$(rbenv init - zsh)"
rbenv local 3.2.2
gem install bundler
bundle install
bundle exec jekyll serve
```

## 📝 日常使用

推荐的工作流程：
1. 在本地编辑文件
2. 推送到GitHub
3. 在线查看效果
4. （可选）配置好本地环境后可以先本地预览再推送

## 🎯 下一步

立即推送到GitHub查看你的新网站！所有内容都已经准备好了。

