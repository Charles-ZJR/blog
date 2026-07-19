---
title: Hexo博客部署流程记录
tags: Hexo
---
# Hexo+GitHub Pages部署关键流程
1. 安装Git、Node.js，安装Hexo脚手架
2. GitHub创建仓库
3. 本地初始化Hexo项目，本地预览调试
4. 安装部署插件，配置_config.yml部署仓库信息
5. 配置Git用户名、邮箱
6. 执行`hexo clean && hexo g && hexo d`部署至GitHub
7. 仓库开启GitHub Pages，访问博客站点
8. 新增文章只需在source/_posts添加md文件，重新执行部署命令更新