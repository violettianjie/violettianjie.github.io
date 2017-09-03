# Tianjie's blog  20170902 

https://violettianjie.github.io/

感谢@weihaisheng 对建立这个github pages blog的帮助。

源码forked from camscofie/camscofie.github.io。


[参考文档：](http://beiyuu.com/github-pages)

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
