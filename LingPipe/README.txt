一、            LingPipe介绍

LingPipe 是alias公司开发的一款自然语言处理软件包，包括主题分类、句题检测、字符语言建模等十余个模块。而且文档完整，甚至每一个算法都有论文参考。更难能可贵的是它支持中文。

官方地址：http://alias-i.com/lingpipe/

下载地址：http://alias-i.com/lingpipe/web/download.html

LingPipe分为两个大块，一块是LingPipe核心文件，另外一块是LingPipe的模型类。需要支持中文的话需要下载Chinese Word Segmentation模块。

 

二、            环境

1. 操作系统：windows7，X86，32位

2. Java JDK1.6

3. Eclipse3.4

4. LingPipe4.1

 

三、            配置步骤

(1) 新建一个名为SentimentAnalysis工程 :

a) 点击菜单中的File >> New >> Project， 选择new project wizard下拉列表中的Java Project from Existing Ant Buildfile。

b) 点击next，在Project Name后输入SentimentAnalysis。

c)点击Browse，找到$LINGPIPE/build.xml文件。$LINGPIPE是指LingPipe解压缩后所在的根目录。

(2) 设置classpath

a) 点击主菜单的Project，选择Properties

b) 选择Java Build Path，点击Libraries

c)点击Add External JARs，选择$LINGPIPE/lib/junit-3.8.1.jar

d) 点击OK