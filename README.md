# evoxuan.cn 跳转入口

此仓库仅将 evoxuan.cn 和 www.evoxuan.cn 的浏览器访问转向 https://evoxuan.com。

GitHub Pages 从 main 分支根目录发布，自定义域名设为 evoxuan.cn。DNS 指向 GitHub Pages，证书签发后开启强制 HTTPS。

JavaScript 跳转保留原网址的路径、查询参数与锚点；无 JavaScript 时通过 meta refresh 返回主站首页。404.html 与 index.html 使用相同跳转页。此实现为浏览器跳转，不是服务器 HTTP 301。
