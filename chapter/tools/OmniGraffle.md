## 最佳工程实践—思维利器OmniGraffle

OmniGraffle是由The Omni Group制作的一款绘图软件，它曾获得苹果设计奖。

OmniGraffle可以支持流程图、逻辑图或者网页产品模型设计等，功能非常强大。与Graffle对应的是在Windows平台广泛应用的MS Visio（Graffle这个词据说就是为了和Visio区分而硬造出来的），关于这两个产品的用户体验对比，本文会稍有涉及。

关于它的使用细节——术的方面，建议读者直接参考帮助文档或平台上其他作者的教程。本文重点想探讨的，是在工程实践中的一些方法论——跟“道”有关的一些个人体会。

##（一）思维可视化

   一般人的大部分思考过程都是杂乱无序的，没有逻辑的，最后也没法形成有效的沉淀，更无法找到清晰的结论。不是所有的人都是天生就有很好的逻辑的，但是逻辑是可以训练的，只要你懂的把自己的思维进行可视化的展示、分析和整理。

常见的思维可视化模型
1. 放射状规整（思维导图、鱼骨图）－－以后专门讨论（例如MindManager等）

2. 层次化规则（架构图、组织结构图）

3. 线性化规整（路径图、时间线）

4. 矩阵式规则（SWOT 分析、商业模式画布）



##（二）数据流

概要数据流，可以快速梳理出数据流向，顺手还能体现数据模型的结构关系。

当然有人要说了，用PowerDesign甚至Excel也可以啊？  Re:是的。但你不觉得这样的图简约明了，用着很爽嘛？还可以直接贴到PPT呢，生活如此乏味，能让工作更有趣，也是保持和提高生产力啊！

![数据流示例](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-9.png)

##（三）业务流



第一步：确定边界、关键里程碑，画出全局流程图。
  开始可能不太明了，或者中途有新的变更，但是不要紧，只要搞清楚起点和终点，解决从哪里来，到哪里去的终极问题，人生就简单了！

所谓纲举目张，确定框架以后就可以集中精力各个击破了。

![概要总图](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-10.png)

第二步：针对不同子流程各个击破

![子流程1](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-14.png)

![子流程2](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-13.png)


第三步：不仅仅是几个框

完成第二步之后，传统语境下的流程图就完成了。但是，作为一个有追求的演员，似乎还可以尝试点什么。

突然，一道灵光撞击出来新的想法。事不宜迟，马上记下来。拖几个元素，插入表格、贴上截图，简单的概要原型页就出来了。

借用IOS风格的搜索栏，把个网页原型整得颇有大写意风格，真是神来之笔！哈哈

![概要原型图](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-11.png)

##（四）文档归集

在工程实践中，项目或产品文档的管理从来都是一个难题。

从初识阶段开始，产品、设计、开发、测试、运营团队在组织架构上可能是分离的，大家本能地按自己的风格习惯写文档，即使是最重要的几个文档，也常常是Visio、PowerDesign、Word、PPT等各种格式混杂，每种文档可能还有软件版本的兼容性差异。

再加上积年累月的人员更迭、团队重组，各种混乱交接，有时查一个简单的问题，都可能要打开电脑上所有的办公软件、十几个窗口。这是要疯掉的节奏，非常非常低效！

基于OmniGraffle良好的兼容特性，完全可以将关键文档整合到一个Graffle文件，不但可以为当前进行的工作中保持迭代、保护成果，还能持续收拢、归纳、索引关键信息，为后续的改进优化打下好的基础。

![文档树](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-3.png)

![开局索引](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-6.png)

![跳转特性支持的动作](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-7.png)

切换版面、显示／隐藏图层、高亮、运行脚本、打开文件等等


添加动作
多类型分发：支持导出Pdf/PNG/HTML/Graffle模版等等

导出的Pdf文件也是可以跳来跳去的哦！



##（五）构建自己风格的组件库

Graffle和Visio一样，提供了扩展资源库的支持，想要什么组件，搜一搜就有了。

![检索扩展资源库](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-8.png)

然而很多时候，我们面临问题不是缺少资源，而是资源太多，无法快速作出选择。
 正如制造工厂里的模具，码农的代码库，有逼格的人一定受不了拖个按钮都得搜索、调色半天。Graffle自带的资源、以前设计的组件、搜罗来的图片/PPT/Visio资源，日常工作中新发明的兵器，最好分门别类放到一个专门的版面。

从最原始各种大小字体、点、线条、箭头开始，逐渐积累起组件，甚至样板页，不断吸收、调整、优化，愈积愈厚，直至形成自己的风格，是不是有点像逍遥派的北冥神功？

当然，不排除牛人们是从一开始就可以开发出好几套不同Style的套装。

Anyway,殊途同归，我们这种智商低的就用努力弥补吧，哈哈！

![develop Own Style](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-8.png)

##（六）技术资产保护

从Visio迁移

可以直接打开MS Visio文件,并在此基础上继续编辑。这个特性对于准备从Windows平台迁移过来的用户来说至关重要。
![打开Visio文件](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-1.png)

从其它工具迁移（Axure/Image/截图）
![从Axure迁移](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-2.png)


##（七）自动布局

坑爹的自动布局！
OmniGraffle新建文件的初始设置默认是自动布局的。

每当你增加一个元素，调整一下位置，command+S , 我去！！刚才的努力白费了，它会按照一套匪夷所思的对齐规则重新布局！ 除了非常简单的图形，是在想不出实际工作中有什么东西是按照经典原型排列的。

好吧，我承认，因为这个坑爹的原因。我大概几个月的时间不知道怎么用这玩意，差点放弃！！

![自动布局-误区](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-8.png)

适用场景
虽然开始在自动布局上踩了坑，但是这招在某些情况下还是非常有用的，例如下面这个，不是美术系的怎么可能画这么圆?  还是那句话，特性很多，都有适用范围，合适就好。
![自动布局-适用场景](http://o8m8ngokc.bkt.clouddn.com/Tools-Mac-OmniGraffle-16.png)

<hr>
更多精彩内容，请扫码关注公众号：@睿哥杂货铺  
[RSS订阅 RiboseYim](https://riboseyim.github.io?product=ebook&id=roadofwriter)
