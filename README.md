
hexo+github快速构建博客  

文档: [Hexo](https://hexo.io/zh-cn/docs/)
---
相关执行命令:  

git提交需全局设置 -  git config --global credential.helper wincred  

hexo生成网页 - hexo g  

hexo服务 - hexo s  

hexo部署 - hexo d  

(.deploy_git,node_modules,public,db.json文件就在提交的时候自动忽略)  

生成的public文件就是常规使用的文件,放在github.io中直接启用index.html就自动引入相关文件展示页面
