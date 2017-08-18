[css规范](https://github.com/necolas/idiomatic-css/tree/master/translations/zh-CN) 

补充几点

1. 命名尽量做到有意义
2. 几个单词组合的变量名之间有 "-" 分隔 
3. 选择器能少写尽量少，没必要详细到每一层级
4. 缩进还是2个空格为好
5. 尽量不使用ID选择器
6. 注意些属性声明的顺序


### SCSS
[SCCS参考](https://github.com/Zhangjd/css-style-guide)

补充几点
1. 可以将一些整站的常用属性比如颜色字体等定义成变量, 单独存一个文件
css 组织方法 [参考文章](http://mp.weixin.qq.com/s/0dvbSwACJVOG-JXDUMp4mQ)


拿以往的经验来谈，首先在页面开发之前需要对页面进行细致的研究观察。当做找茬的游戏，发现页面之间的一些共同点，哪些样式是可以复用的，哪些有个个性化不能复用的，哪些是所有项目之间可以共用的。
css 的各种组织方法，其实也是那css按照某些原则再做细分，比如布局上的样式，内容呈现的样式

在Vue中，情况又会有所不同，样式可以写在单独的组件中而不是css文件中。scoped和 非scoped，又会有不一样的情况。建议还是带上scoped的。



### postCSS 待补充


