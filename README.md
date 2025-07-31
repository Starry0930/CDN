# CDN
解决方法：

https://cdn.jsdelivr.net/gh/Starry0930/CDN@main/test.jpg

使用 cdn.jsdelivr.net 未受污染的子域：
fastly.jsdelivr.net，由 Fastly 提供 本站使用

gcore.jsdelivr.net，由 G-Core 提供

testingcf.jsdelivr.net，由 CloudFlare 提供

使用国内的静态库：
cdn.staticfile.org，七牛云和掘金的静态资源库

cdn.bytedance.com，字节跳动静态资源公共库

cdn.baomitu.com，360 前端静态资源库

将需要的静态资源下载到本地

第一种只需将博客主题的 HTML 文件中 jsDelivr 链接里的 cdn 替换为子域名即可；第二种需要在这些国内网站上搜索 JS 库的名字，然后复制搜索结果给出的链接，再替换掉对应的 jsDelivr 链接；第三种是替换为本地路径。
