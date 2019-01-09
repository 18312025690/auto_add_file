# auto_add_file
# 前言

公司的app项目，主要文件就是js、css、html、scss，所以每次新加一个页面的时候就要分别在以上四个目录创建对应的文件，创建完之后的html js 还要去写过的页面拷贝一份代码过来才行。然后我就想写个小插件去自动地帮我生成文件，还能加上模板。

写起来也是挺顺利，后期还会继续调优，主要就是分离一下代码。本来是想优化后再放到github上的，可能优化这一块需要的时间不少，所以就先放上来了。模板是用了 nunjucks 的模板，因为html里有引入很多公共文件，所以就不能直接单一的写入，而是需要用模板能采用变量的方式去写入，这样就能更好的去帮我们初始化页面

## 使用

> npm i 

> npm run add 

> run add 之前注意需要修改一些配置

> 一个是在index.js 里面的 # fileConfig 里 #addDir 和 # addFileName。具体可以去看一下index.js代码注释。还有一个就是views里面的模板 这个没有了解过的可以去看去nunjucks的资料，上手挺容易的 nunjucks 传送门 》》 https://nunjucks.bootcss.com/


# 最终目标

1、分离项目 配置好之后 可能使用命令行来添加文件

2、基于一 发布到npm上

# 题外

> 准备着手开发一个 自动测试的项目 大家有问题可以提issues哈 对您有帮助的话也希望您可以给个星星~(这写项目主要都是个人练习用的，各位大佬有兴趣的可以加我wx一起写哈18312025690 添加的时候麻烦加个备注)


