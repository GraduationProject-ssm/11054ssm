# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 11054ssm网上报名系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1Kp48e9EtU?p=98)


# 第1章 系统分析
## 1.1 技术可行性
1.1.1　技术成熟、开发迅速

从知识交流平台系统所需要实现的功能、性能等等各方面条件出发，现在的技术条件完全可以实现，无论从硬件方面还是软件方面。其开发所需要的软件环境为：中文Win7 

或以上的操作系统；eclipse集成开发环境，IIS10.0 服务器，mysql5.5数据库服务器。

系统采用 JAVA语言开发和SSM框架，可以将任务进行细化，能够提供各种控件和组件、

标签，有效提高了程序开发速度。经济可行性网上报名系统是本人的毕业设计成品，由个人完成，所需要的硬件需要一台可上网上电脑，无需要进行另外的购买，而所需要的开发软件也可以下载使用，因此开发的成本比较低。此外，系统的成功开发具有一定的经济价值。可见，网上报名系统管理系统的开发在技术上具有可行性。
### 1.1.2经济可行性
本系统是网上报名系统，面向的是电脑考生所以成本并不高，维护和调试只需个别成员参与，所以人力投入也很少。虽说人力和资金的投入不是很多，但是面临的增益是十分的可观尤其是从长远角度来看，所谓知识是无价的，而需要面临很多困扰，而网上报名系统很大程度上解决了这一问题，未来，需要投入到资源保管的人十分的少，不需要很多的人就够了，人少却又能保证信息的安全，那么对人员的资金就可以减少不少，并且工作人员并不会很辛苦。

使用的数据库是MySQL数据库，对于交流网站来讲是很低的成本，大大减少了空间，而原有的空间则可以用来处理别的事物。
### 1.1.3技术可行性
在技术方面也是完全可以做到的，目前所拥有的技术足以开发出一个完整的网上报名系统。因为面向的对象较为单一，所以所需要的技术并不复杂，皆是学校内所学到的知识，而且所需要的工具也不是很复杂。使用java编写页面和mysql连接数据库，使用最简单的MySQL数据库，维护起来也是十分的容易，而本系统是基于B/S的结构创建的，也是比较简单明了的。所以从技术方面来讲也是可以实行的。
### 1.1.4操作可行性
本系统的开发，运用的是基础技术，面向的是单一群体，所以不会造成信息拥堵和崩溃的局面，所以运行时是可以较快的执行考生的命令的。而存在于页面的数据都会以表单的形式传送到数据库，所以不会造成混乱。

就目前而言，计算机普及的时代，学习维护和运用系统并不会很困难，所以人员方面是可以实行的，而且系统可以运用在不同的计算机上，所以这里也是可以运行的。
### 1.1.5 时间可行性
就时间而言，因为项目并不是很庞大，所以是可以在时间范围内完成的。但是需要好好把握时间的安排，因为本次毕业设计是单人的，所以需要自我监督和敦促，不能见异思迁，一定要先有一个明确的时间规划表。才能在有限的时间内完成本系统。
### 1.1.6 法律可行性
本系统所用的技术和资源均是合法的，引用的部分都有注明，参考文献等也是合乎规定的，是属于个人的创作成果，没有涉及到危害他人的知识产权的行为。
## 1.2需求分析
针对现存的问题和需要，通过功能需求的分析，特建立了数字化、信息化的网上报名系统。

本系统主要包含了管理员、考生二个权限。不同的权限对应相应的功能模块的需求，管理员权限的级别是最高的，所以所对应的需求是最多的，下面根据不同的权限分别简单阐述一下各个权限的需求。
## 1.3业务流程分析
总体业务流程：以管理员的身份在登录页面输入账号和密码，经过数据库身份验证，验证成功后登录系统主页，可以使用系统，管理系统等功能操作 。
## 1.4数据流程分析
数据流图的简称为DFD，是通过使用图形的方法对系统所具备的逻辑功能进行阐述，描述系统数据的流向和逻辑变换。由于该方法能将难以阐述的问题进行表述，因此被开发者广泛应用，是当前应用范围较为广泛的结构化系统分析方法。

零层数据流程是流程中最抽象的一层，它包括了登录管理、管理员功能管理和检索维护管理等功能模块，在登录模块使用到的数据存储有考生、级别专业、报名信息、考生成绩等，管理员功能管理模块需要的存储是管理员添加考生信息文档、考生管理文档、删除信息文档，检索维护是通过以上这些文档信息通过关键词进行搜索。

系统的1层数据流图如下图所示。

![](/md/blog.001.png)

图3-2系统数据流图（1层）

2层为管理员操作后台数据流图，管理员可以分别通过添加、修改和删除来进行管理，如下图所示：

![](/md/blog.002.png)

## 1.5开发意义
考生往往因为不能及时的查询到心仪的网上报名而造成许多烦恼。另一方面，网上报名系统信息网站没能进行系统的管理与维护使网上报名信息没能及时的更新。而传统的报名系统管理，采用的还是人工查询、手工备案、人工查询的方式。但是随之人数的增多这种管理方式的工作量不断加大，这种做法就存在费时费力、缺乏时效性、不利于调动人员的积极性等缺点。一旦网站建立好之后，一方面，考生可以在第一时间在系统里查询所需的信息，另一方面，系统还可以管理信息，就减少了人工处理的工作量。

建立本网上报名系统信息管理是为了通过管理者对信息的分享管理，以方便考生对自己所须信息的查询，一旦查询到自己所需要的信息，考生便可以从系统中获得信息，以方便在线查询。如果没有查询到自己所需求的信息，也可以提醒管理者增添。这样，本系统旨在建立考生、管理员二者之间的桥梁关系，从而使考生能及时有效的从管理者手中呈现到信息。所以我们认为建立一个网上网上报名系统信息管理是非常必要的，其方便高效、简单快捷的管理模式是很有使用性的[3][4]。 
## 1.6研究内容
1. 不同管理员的登录问题：根据管理员的类别（管理员与考生）实现管理员操作权限的区分并显示不同的操作界面。
1. 数据库的连接问题：数据库连接为系统中的关键技术。
1. 数据的一致性和安全问题：本系统必须保证数据的一致性和安全，才能实现有效的管理。不能让没有权限的管理员对数据进行操作并且定期对数据库进行备份。
1. 界面开发：系统界面的设计很重要，要使界面具有亲和力。
1. 分析信息化现状；
1. 研究网上报名系统的现状及存在的问题；
1. 研究系统平台的总体架构、总体设计、数据库设计、数据库安全设计及功能设计；
1. 研究平台各个子系统的功能及实现的方法、信息技术的融合、信息安全技术的维护；
1. 进行网上报名系统的功能设计。

11
![](/md/blog.003.png)
# 第2章 主要技术和工具介绍
## 2.1 B/S结构
B/S模式也就是浏览器/服务器模式，它的界面部分是在浏览器端展示，而主要工作是由服务器端进行实现的，考生的请求由浏览器端提交给服务器端进行处理，而服务器将处理结果反馈给浏览器端，在浏览器端界面描画给考生查看。采用B/S模式不仅可以避免考生必须安装网上报名系统软件才能开发系统或者访问系统的局限性，而且更加便利[12]。
## 2.2 java技术
java是一种跨平台的网页技术，最终实现网页的动态效果，与 JSP技术类似，都是在HTML中混合一些程序的相关代码，运用语言引擎来执行代码，java能够实现与管理员的交互，方便管理员的使用。

java技术具有诸多优点，可以忽略所使用的平台，实现仅需一次编写就能够到处运行使用，而且还具有很好的安全性和多平台支持的特性，能够在任何平台的任何环境中进行开发，进行系统部署和环境扩展。它也有属于自己的功能强大的开发工具的支持，并且可以通过很多渠道免费得到，这就为java技术的传播也准备了条件[5][6]。

## 2.3 SSM三大框架
1.Spring的优势:
通过Spring的IOC特性，将对象之间的依赖关系交给了Spring控制，方便解耦，简化了开发。

2.Spring MVC的优势:
SpringMVC是使用了MVC设计思想的轻量级web框架，对web层进行解耦，使我们的开发更简洁。

3.Mybatis的优势:

数据库的操作(sql)采用xml文件配置，解除了sql和代码的耦合，提供映射标签，支持对象和和数据库orm字段关系的映射，支持对象关系映射标签，支持对象关系的组建提供了xml标签，支持动态的sql。

## 2.4 MySQL数据库
MySQL是目前中小型企业进行软件系统开发时广泛使用的传统关系数据库之一，特别是近年来在 Oracle 公司的管理下，MySQL数据库的性能有了很大的提升，而且支持的功能也更加丰富。MySQL作为最早的开源关系数据库之一，最初是由瑞典的数据库公司 MySQLAB 进行开发维护的，现归甲骨文公司管理。MySQL作为最为流行的开源关系数据库，是Web应用开发者进行Web 应用开发时的首选数据库。MySQL数据库虽然是开发数据库产品，但是在广发MySQL使用者的共同维护下，MySQL本身的性能并不差。MySQL作为传统的关系数据库，与其它传统的关系数据库并无大的差别，在 MySQL数据库中，数据根据数据库使用者的定义被存储于不同的数据库表中，而且考生可以定于不同的数据库来存放不同的数据表，这和目前新兴的非关系数据库数据存储方式有着很大的不同。MySQL数据库中数据的分表分库存储方式能够最大程度的避免数据同步代码的性能损耗，使得数据库的存取速度有了很大提升，而且同时保持了很大的灵活性。因此目前的中小型软件系统大多采用 MySQL数据库进行系统数据的存储。

![](/md/blog.004.png)

图3-4系统数据流图（2层）

41
![](/md/blog.005.png)

# 第4章 系统设计
## 4.1系统结构设计
系统设计主要是管理员登录后对整个系统相关操作进行处理，可进行管理员的添加和删除，管理员模块如下：首页、个人中心、考生管理、级别专业管理、报名信息管理、考生成绩管理、系统论坛、系统管理等。

考生模块：首页、个人中心、报名信息管理、考生成绩管理等。

前台首页：首页、级别专业、系统论坛、系统公告、个人中心、后台管理、在线客服等多个模块，系统的功能结构图如下图所示。

`     `![](/md/blog.006.png) 

图4-1系统功能结构图
## 4.2开发流程设计
系统流程的分析是通过调查系统所涉及问题的识别、可行性、可操作性、系统分析处理能力等具体环节来调节、整理系统的设计方案以确保系统能达到理想的状态。这些操作都要从注册、登录处着眼进行一系列的流程测试保证数据库的完整，从而把控系统所涉及信息管理的安全、保证信息输入、输出正常转换。然后，通过实际操作完成流程图的绘制工作。

网上报名系统的开发对管理模块和系统使用的数据库进行分析，编写代码，系统测试，如图4-2所示。

![](/md/blog.007.png)

图4-2开发系统流程图

## 4.3数据库设计
系统里尤为关键的部分是在数据库方面，需要十分清晰的思路，所以从开始的设计时需要做到确立模块之间的联系，从而可以很明确的建立表间的联系和表中所需的内容。设计数据库还有一点是减少表的繁杂的创建，所以联系很关键，可以大大的减少，数据表中重复的事项。由此可以保证数据的完整和统一，不会造成数据的错误和重复，并且可以使数据得到数据库安全的保护，会使考生更加的放心。
### 4.3.1 E-R图设计
概念设计是整个数据库设计的关键，在概念设计阶段，由需求分析得到了E-R模型。E-R图是识别功能模型与数据模型间关联关系的，在主题数据库的抽取和规范化的过程中，采用的是简化的E-R图表示方法，从而避免过繁过细的E-R图表示影响规划的直观和可用性。是对现实世界的抽象和概括，是数据库设计人员进行数据可设计的有力工具，能够方便直接地表达应用中的各种语义知识，令一方面它简单、清晰、易于考生理解。

管理员实体包括管理员名称、密码二个属性。

管理员体ER图如下图所示。

![](/md/blog.008.png)

图4-3管理员ER图

考生信息：考生账号、考生姓名、密码、年龄、性别、联系电话、邮箱、身份证、头像、专业、省份、学校ER图如下图所示。

![](/md/blog.009.png)

图4-4考生信息ER图

级别专业信息：考试名称、专业名称、封面、年龄要求、考试地址、报考费用、考试时间、倒计结束时间、报考条件ER图如下图所示。

![](/md/blog.010.png)

图4-5级别专业信息ER图

考生成绩信息：考试名称、考生号、考生帐号、考生姓名、考生成绩、登记时间ER图如下图所示。

![](/md/blog.011.png)

图4-6考生成绩信息ER图


根据系统各个实体的关系，得出系统的总体ER图。

系统总体ER图如下图所示。

![](/md/blog.012.png)

图4-7系统总体ER图
### 4.3.2表设计
数据库表是数据库重要的组成部分，其实数据库只是一个框架，数据库表才是数据库的本质，本系统数据库表如下：

allusers表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|username||150||255||
|3|pwd||150||255||
|4|cx||150||255||
|5|addtime|DateTime|8||19||

baomingxinxi表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|3|kaoshimingcheng||150||255||
|4|kaoshishijian|DateTime|8||255||
|5|kaoshenghao||150||255||
|6|baokaofeiyong|DateTime|8||255||
|7|kaoshidizhi||150||255||
|8|zhuanyemingcheng|DateTime|8||255||
|9|kaoshengzhanghao||150||255||
|10|<p></p><p>kaoshengxingming</p>|DateTime|8||255||
|11|xingbie||150||255||
|12|zhuanye|DateTime|8||255||
|13|shengfen||||||
|14|xuexiao|DateTime|8||255||
|15|lianxidianhua||||||
|16|nianling|DateTime|150||255||
|17|touxiang||||||
|18|baomingshijian|DateTime|150||255||
|19|beizhu||||||
|20|sfsh|DateTime|150||255||
|21|shhf||||||

jibiezhuanye表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|3|kaoshimingcheng||150||255||
|4|zhuanyemingcheng|DateTime|8||255||
|5|fengmian||150||255||
|6|nianlingyaoqiu|DateTime|8||255||
|7|kaoshidizhi||150||255||
|8|baokaofeiyong|DateTime|8||255||
|9|kaoshishijian||150||255||
|10|baokaotiaojian|DateTime|8||255||

kaosheng表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|4|kaoshengzhanghao||150||255||
|5|kaoshengxingming||150||255||
|6|mima|DateTime|8||||
|7|nianling|||8|||
|8|xingbie|DateTime|8||255||
|9|lianxidianhua||||||
|10|youxiang|DateTime|8||255||
|11|`	`shenfenzheng||||||
|12|touxiang|DateTime|8||255||
|13|zhuanye|DateTime|8||255||
|14|shengfen|DateTime|8||255||
|15|xuexiao|DateTime|8||255||

kaoshengchengji表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|4|kaoshimingcheng||150||255||
|5|kaoshenghao||150||255||
|6|kaoshengzhanghao|DateTime|8||||
|7|kaoshengxingming|DateTime|||||
|8|kaoshengchengji||||255||
|9|pingyu||DateTime|8|||
|10|dengjishijian||DateTime|8|255||













# 第5章  系统实现
## 5.1登录模块的实现
系统登录模块后台登录模块，为确保系统安全性，系统操作员只有在登录界面输入正确的管理员名、密码单击“登录”按钮后才能够进入本系统的主界面。

管理员登录流程图如下所示。

![](/md/blog.013.png)

图5-1管理员登录流程图


## 5.2管理员模块的实现
## 管理员通过输入考生名，密码、角色信息进行系统登录，效果如下图所示5-2所示
![](/md/blog.014.png)

图5-2管理员登录界面
## 5.2.1考生管理
## 管理员信息添加考生管理功能主要指对其考生账号、考生姓名、密码、年龄、性别、联系电话、邮箱、身份证、头像、专业、省份、学校等一些基本信息的添加、删除和修改。考生管理效果如下图所示5-3所示

![](/md/blog.015.png)

图5-3 考生管理界面

## 5.2.2级别专业管理
## 管理员对级别专业管理添加主要指对其考试名称、专业名称、封面、年龄要求、考试地址、报考费用、考试时间、倒计结束时间、报考条件等一些基本信息的添加、删除和修改。级别专业管理添加效果如下图所示5-4所示


![](/md/blog.016.png)

图5-4级别专业管理界面


## 5.2.3考生成绩管理
## 管理员通过考生成绩管理页面查看考试名称、考生号、考生帐号、考生姓名、考生成绩、登记时间等进行添加、删除、修改以及查看等操作。效果如下图所示5-5所示


![](/md/blog.017.png)

图5-5考生成绩管理界面

5.2.4系统论坛
## 管理员通过系统论坛页面查看跳转标题、考生名、状态等信息进行操作或修改删除，效果如下图所示5-6所示

![](/md/blog.018.png)

图5-6系统论坛界面

5.2.5系统管理
## 管理员通过系统管理页面查看系统公告、在线客服、轮播图管理等信息进行操作或修改删除上传图片、发布公告、在线回复，效果如下图所示5-7所示

![](/md/blog.019.png)

![](/md/blog.020.png)

图5-7系统管理界面

## 5.3前台模块的实现

前台首页浏览，通过内容列表可以获取网站首页、级别专业、系统论坛、系统公告、个人中心、后台管理、在线客服等信息操作内容，如图5-8所示。

![](/md/blog.021.png)

图5-8前台界面图

` `5.3.1级别专业
##

级别专业，通过内容列表可以获取考试名称、专业名称、封面、年龄要求、考试地址、报考费用、考试时间、倒计结束时间、报考条件查看等操作，如图5-9所示。

![](/md/blog.022.png)

![](/md/blog.023.png)

图5-9前台级别专业界面图

5.3.2系统论坛

系统论坛，通过内容列表可以进行发布帖子等操作，如图5-10所示。

![](/md/blog.024.png)

图5-10系统论坛界面图

5.3.3个人中心

个人中心，通过内容列表可以获取考生账号、考生姓名、密码、年龄、性别、联系电话、邮箱、身份证、头像、专业、省份、学校等信息可进行注册，注册完成通过输入考生名、密码进行登陆操作，如图5-11所示。

![](/md/blog.025.png)

![](/md/blog.026.png)

图5-11个人中心界面图



5.4考生模块的实现
## 5.4.1考生登录
` `考生通过输入考生名，密码，角色等信息进行系统登录，如图5-12所示。




![](/md/blog.027.png)



图5-12考生登录界面图
##



5.4.2报名信息管理

在报名信息管理页面可以通过填写考试名称、考生号、专业名称、考生账号、性别、专业等内容并进行添加以及查看。效果如下图所示5-13所示

。

![](/md/blog.028.png)

![](/md/blog.029.png)

图5-13报名信息管理界面图

5.4.3考生成绩信息
## 在考生成绩管理页面可以通过考试名称、考生号、考生帐号、考生姓名、考生成绩、登记时间等内容并进行查看。效果如下图所示5-14所示
。

![](/md/blog.030.png)图5-14考生成绩管理理界面图

# 系统测









