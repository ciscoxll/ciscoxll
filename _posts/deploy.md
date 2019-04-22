title: 部署blog
date: 2013/9/12 21:30:00
---

1.node安装
* 安装 Node.js 的最佳方式是使用 nvm。
```bash
wget -qO- https://raw.github.com/creationix/nvm/master/install.sh | sh
export NVM_DIR="$HOME/.nvm"
source ~/.bashrc
command -v nvm
nvm install stable
```
2.安装 Hexo
```bash
npm install -g hexo-cli
hexo init blog
cd blog
npm install
hexo server -p 80
```
3.基本目录
```
# Markdown 文件目录
/blog/source/_posts
# 静态文件目录
/blog/public
```

4.生成静态文件
```bash
hexo generate
```




参考 https://hexo.io/zh-cn/

