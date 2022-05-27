# TianJie's Blog  20170902 

https://violettianjie.github.io/

## 为什么要开博客？ 

- 修正、完善对事物的认识
- 分享我有的一切, 参考博客 [Derek Sivers]( https://sivers.org/sharing)

## 感谢

1、@weihaisheng 对建立这个github pages blog的帮助。

2、源码forked from camscofie/camscofie.github.io。源码来源 http://beiyuu.com/。

## 参考资料

- [参考文档：](http://beiyuu.com/github-pages)

Jekyll基本结构

Jekyll的核心其实就是一个文本的转换引擎，用你最喜欢的标记语言写文档，可以是Markdown、Textile或者HTML等等，再通过layout将文档拼装起来，根据你设置的URL规则来展现，这些都是通过严格的配置文件来定义，最终的产出就是web页面。

基本的Jekyll结构如下：

|-- _config.yml
|-- _includes
|-- _layouts
|   |-- default.html
|   `-- post.html
|-- _posts
|   |-- 2007-10-29-why-every-programmer-should-play-nethack.textile
|   `-- 2009-04-26-barcamp-boston-4-roundup.textile
|-- _site
`-- index.html
