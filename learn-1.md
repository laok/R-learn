#R 语言学习笔记

##1.安装

[R for Mac OS X](http://cran.r-project.org/bin/macosx/)

[R for Mac OS X FAQ](http://cran.r-project.org/bin/macosx/RMacOSX-FAQ.html)

[GUI R](http://r.research.att.com)

##2.运行
打开终端

`open Terminal.app`

`$ R`

##3.基本语法


    $R: 
    > getwd() 	#获取环境路径
    > dir()		#环境路径下列举文件
    > setwd("/Users/xx/examples") #设置环境路径，xx指登录用户名

#### 说明	
1. R语言是解释性语言，不是编译性语言
2. 函数以（）结束，如果不写（），则输出关于改函数的相关信息

##网络资源


1. [http://www.rexamples.com](http://www.rexamples.com)
2. [R demos](http://www.mayin.org/ajayshah/KB/R/)
3. [Rexamples](http://www.stat.pitt.edu/stoffer/tsa3/Rexamples.htm)
4. [数据科学与R语言](http://xccds1977.blogspot.com)
5. [R语言中文网](http://www.r-china.net/portal.php)


###[书籍推荐来源](http://xccds1977.blogspot.com/2013/02/r.html)
一、初学入门：
《R in Action》
《The Art of_R Programming》
入门者可首选两本，前者从统计角度入手，分高中低三部分由浅入深的讲解了如何用R来实现统计分析，另外此书已经有中文版面世。后者从程序编写的角度入手，对R的本身特点进行了清晰的介绍。中文版应该快有了。
更新：《learning R》
这本书没有单纯的讲语法，而是和数据分析的流程结合了起来，从数据获取到数据整理再到分析和报告，有一气呵成的感觉，此外最后两章讲如何写稳健的R代码以及写包都是非常精彩的。

二、统计进阶：
《A Handbook of Statistical Analyses_Using_R》
《Modern Applied Statistics With S》
这两本书基本上涵盖了统计的一些高阶内容，例如多元分析、多层回归模型、荟萃分析、生存分析等内容。案例丰富，公式不多，值得反复学习参考。

三、科学计算：
《Introduction to Scientific Programming and Simulation Using R》
除了统计分析外，此书独特之处在于使用R来做数值分析，如求根，最优化，数值积分。还包括了一些常见的模拟技术。书后的习题和最后的案例非常有用。该书的中文版据说还在翻译。

四、数据挖掘：
《Data Mining with R_ Learning with Case Studies》
《Machine Learning for Hackers》
两本侧重于数据挖掘的R书，全是以案例为线索，示范的代码量很大。跟一遍下来会有很大的收获。
更新：《An Introduction to Statistical Learning》
这本书可以说是另一本数据挖掘大作《The Elements of Statistical Learning》的R实现手册，体系结构基本一致，更强调用R来实现，更难得的地方是提供了很好的习题。

五、数据绘图：
《ggplot2 Elegant Graphics for Data Analysis》
ggplot2还有什么好说的呢，R中最优秀的绘图包，但由于近期该包升级很快，这书显得有些过时。好在中文版进行了大幅更新，即将面世。
更新：《R Graphics Cookbook》
这本书也是RStudio公司的人出的，似乎是Hadley的学生吧，主要是各种ggplot2包的例子，也包括了用其它包来画图，建议通读一遍。

六、参考手册：
《R Cookbook》
《R in a Nutshell》
有时候我们需要类似词典的案头参考手册，以方便随时查阅。又或者可以通读一遍以查漏补缺。上面两本书虽然有些厚度，但仍然推荐之。后者的中文版也在翻译状态。

七、高级编程：
《R Programming for Bioinformatics》
《software for data analysis programming with R》
如果你是初学者，不要去看上面两本书。如果你想进阶为专家级R用户，那你需要精读它们。前者讲解了R少为人知的一面，例如字符处理、正则表达和XML，还有报错处理以及与其它语言的交互。后者更是编写生产级代码的圣经指南。
更新：《Advanced R programming》
Hadley的力作，只是还没有写完，已经可以从这里看到部分，清楚的讲解了R的函数式编程思想和写R包的各种细节，要迈入R高手，不得不读。