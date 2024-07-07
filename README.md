## 介绍
[docsify-template](https://github.com/mg0324/docsify-template.git)是一个docsify的模板仓库，集成好了常用的插件。

## 快速开始
> 本工具基于node平台，且发布到npm公共仓库。
1. 安装docsify-note-cli和docsify
``` shell
npm install -g docsify-note-cli
npm install -g docsify
```
2. 从模板初始化
``` shell
mkdir test # 修改为自己的项目名，如test
cd test # 进入到项目下
docsify-note init # 初始化，执行完后会下载模板仓库内容到当前文件夹下
```
3. 调整文档标题和内容后，启动服务
``` shell
docsify s
```
4. 访问服务`http://localhost:3000/`

5. 在模板基础上调整配置值为自己的即可快速构建您的在线笔记或文档的基础版本。

真正让您只关注分享内容的书写，**now enjoy it**! 

查看示例，请到[docsify-note](https://mgang.gitee.io/docsify-note/)

## 微信交流群
欢迎加入微信交流群，请加我微信并备注[`docsify-note交流`]，我会拉您进群！

<img style="width:250px;" src="https://mg.meiflower.top/oss/docsify-note/mango-wx.jpeg">

## 已集成特性
1. vue主题 - 可更换为其他主题
2. 搜索 - 官方内置特性
3. 图片放大 - 官方内置特性
4. 代码复制 - [docsify-copy-code](https://www.npmjs.com/package/docsify-copy-code)
5. 字数统计 - [docsify-count](https://www.npmjs.com/package/docsify-count)
6. 分页导航 - [docsify-pagination](https://www.npmjs.com/package/docsify-pagination)
7. 侧边栏扩展与折叠 - [docsify-sidebar-collapse](https://www.npmjs.com/package/docsify-sidebar-collapse)
8. 卜蒜子显示网站访问量 - 默认开启 - [docsify-busuanzi](https://www.npmjs.com/package/docsify-busuanzi)
9. 页脚footer - [docsify-footer-enh](https://www.npmjs.com/package/docsify-footer-enh)
10. 最近更新时间 - [docsify-updated](https://www.npmjs.com/package/docsify-updated)
11. flexible alerts提示信息 - [docsify-plugin-flexible-alerts](https://www.npmjs.com/package/docsify-plugin-flexible-alerts)
12. 阅读进度条美化 - [docsify-progress](https://www.npmjs.com/package/docsify-progress)
13. 问答faq手风琴 - [docsify-accordion](https://www.npmjs.com/package/docsify-accordion)
14. tab选项卡 - [docsify-tabs](https://www.npmjs.com/package/docsify-tabs)
15. 回到顶部 - [docsify-backTop](https://www.npmjs.com/package/docsify-backTop)
16. 文章内右侧目录toc - [docsify-plugin-toc](https://www.npmjs.com/package/docsify-plugin-toc)
17. 百度统计 - [docsify-baidu-tj](https://www.npmjs.com/package/docsify-baidu-tj)
18. giscus评论 - [docsify-giscus](https://www.npmjs.com/package/docsify-giscus)
19. html预览demo - [docsify-demo](https://www.npmjs.com/package/docsify-demo)
20. 引入远程md - [docsify-remote-markdown](https://www.npmjs.com/package/docsify-remote-markdown)
21. drawio文件预览 - [docsify-drawio](https://www.npmjs.com/package/docsify-drawio)
22. 自动加空格 - [docsify-pangu](https://www.npmjs.com/package/docsify-pangu)
23. 图形语言全家桶 - [docsify-kroki](https://www.npmjs.com/package/docsify-kroki)
24. 更新日志模块 - 以navbar形式实现
25. 使用推荐的cdn jsdelivr - 保证国内外稳定快速访问
26. 自定义标题后显示最新文档版本号 - 以`badge`样式实现
27. 自定义广告推荐 - [docsify-ads](https://www.npmjs.com/package/docsify-ads)
28. 支持匿名评论 - [docsify-mango-valine](https://www.npmjs.com/package/docsify-mango-valine)
29. 增加网站的[favicon](https://favicon.io/favicon-generator/)
30. 内嵌PDF预览 - [docsify-pdf-embed-plugin](https://www.npmjs.com/package/docsify-pdf-embed-plugin)
31. 显示仓库共享者 - [docsify-contributors](https://www.npmjs.com/package/docsify-contributors)
32. 集成认证插件 - [docsify-auth](https://www.npmjs.com/package/docsify-auth)