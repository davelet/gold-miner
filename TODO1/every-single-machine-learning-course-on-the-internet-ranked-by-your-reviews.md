> * 原文地址：[Every single Machine Learning course on the internet, ranked by your reviews](https://medium.freecodecamp.org/every-single-machine-learning-course-on-the-internet-ranked-by-your-reviews-3c4a7b8026c0)
> * 原文作者：[David Venturi](https://medium.freecodecamp.org/@davidventuri?source=post_header_lockup)
> * 译文出自：[掘金翻译计划](https://github.com/xitu/gold-miner)
> * 本文永久链接：[https://github.com/xitu/gold-miner/blob/master/TODO1/every-single-machine-learning-course-on-the-internet-ranked-by-your-reviews.md](https://github.com/xitu/gold-miner/blob/master/TODO1/every-single-machine-learning-course-on-the-internet-ranked-by-your-reviews.md)
> * 译者：[davelet](https://github.com/davelet)
> * 校对者：

# 基于评论的机器学习在线课程排名

![](https://cdn-images-1.medium.com/max/2000/1*vBLkfW8S-ZqHb8TmNEW1XA.jpeg)

_Kaboompics 的_[_木头人_](https://www.pexels.com/photo/wooden-robot-6069/)

一年半以前，我退出了加拿大最好的计算机科学课程之一，开始使用线上资源创建我自己的[数据科学研究生课程](https://medium.com/@davidventuri/i-dropped-out-of-school-to-create-my-own-data-science-master-s-here-s-my-curriculum-1b400dcee412#.5fwwphdqd)。我意识到只要通过edX、Coursera 和 Udacity 就能学到所有我需要的东西，而且学习得更快更高效，学费还比大学低！

现在我马上就完成了！我学习了很多数据科学相关的课程而且评估了更多课程的部分内容。我知道了如何选择，也知道了什么技能对于打算成为数据分析家或者数据科学家的学员是必需的。所以我之前开始创建一个评论驱动的用于推荐数据科学领域内各学科最好课程的指导。

在本系列的第一篇指导中我给刚入门的数据科学家们先推荐一些[编码课程](https://medium.freecodecamp.com/if-you-want-to-learn-data-science-start-with-one-of-these-programming-classes-fb694ffe780c#.42hhzxopw)，然后是[概率统计课程](https://medium.freecodecamp.com/if-you-want-to-learn-data-science-take-a-few-of-these-statistics-classes-9bbabab098b9#.p7pac546r)，然后是[数据科学概论](https://medium.freecodecamp.com/i-ranked-all-the-best-data-science-intro-courses-based-on-thousands-of-data-points-db5dc7e3eb8e)，还有[数据可视化](https://medium.freecodecamp.com/an-overview-of-every-data-visualization-course-on-the-internet-9ccf24ea9c9b)。

### 欢迎来到机器学习

我为了这篇指导花费了十几个小时尝试找出截至到 2017 年 5 月的所有在线课程，根据它们的简介和评论抽取关键信息并计算评分。**我最终的目标本来是找出最好的三门课程呈现出来以飨读者。**

为了实现这个目标，我特意到开源社区 Class Central，它的数据库中有数以千计的课程评分和留言。

![](https://cdn-images-1.medium.com/max/1000/1*u1dxHyShejSN3cgXGFQIAA.png)

_Class Central 的_[_主页_](https://www.class-central.com/).

自从 2011 年起，[Class Central](https://www.class-central.com/) 的创始人 [Dhawal Shah](https://medium.com/@dhawalhs) 就一直无可争议的是最贴近在线课程的研究者。Dhawal 个人也帮我一起收集了这个资源列表。

### 我们如何甄选课程

每一门课程都必须满足如下三条准则：

1.  **必须包含大量的机器学习内容**。原则上机器学习应该是首要主题。注意，只涉及深度学习的课程应该被排除，后面会详述。
2.  **必须按需或每隔几个月提供一次。**
3.  **必须是可交互的在线课程，不能使用书本或只读性质的指南**。尽管那些也是学习的途径，但是这里只关注课程。完全的视频教程（也就是说没有测验或课后作业等）也要排除。

我相信我们已经包含了所有符合上述准则值得关注的的课程。鉴于我们从 [Udemy](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14494&RD_PARM1=https%253A%252F%252Fwww.udemy.com%252F) 上面收集了几百门课程，我们只选择其中留言最多、评分最高的课程。

不过由于精力有限，一定还是有可能我们会忽略掉某课程的。如果你发现我们漏掉了一门好课程，请在评论区留言让我们知道。

### 我们如何评估课程

我们从 Class Central 以及其他点评网站汇集了每门课程的平均评分，以此来计算它们的加权平均分。我们阅读了文字评论，通过那些课程反馈来补充分数。

我们根据三个因素进行了教学大纲的主观判断:

1.  **对机器学习工作流程的解释程度**。课程是否描绘了成功运行一个 ML 工程的必要步骤？ 有关典型工作流程的含义，请参阅下一节。
2.  **对机器学习技术和算法的覆盖程度**。 是否涉及了各种技术（例如回归、分类、聚类等）和相关算法（比如分类算法：朴素贝叶斯、决策树、支持向量机等），还是只简单挑选了几个？我们优先考虑的课程覆盖得更多，而不是仅仅介绍梗概。
3.  **对通用数据科学和机器学习工具的使用程度**。课程教学上是否使用了流行的编程语言，比如 Python、R 或 Scala？对这些语言的流行类库使用如何？这些当然不是必需的但是是有用的，所以对这些课程我们略有偏好。

### 什么是机器学习？工作流程如何？

一个流行的定义起源于 1959 年 [Arthur Samuel](https://en.wikipedia.org/wiki/Arthur_Samuel "Arthur Samuel") 的说法： in 1959: 机器学习是计算机科学的一个分支，能够“_让计算机自主学习而无需显式编程_”。实践中，这意味着开发的计算机程序可以根据数据进行预测。就像人类可以根据经验学习一样，计算机也可以。对于计算机，数据 = 经验。


机器学习工作流程是执行机器学习项目所需的过程。尽管单个项目可能不同，但是绝大多数工作流程都需要这么几个通用任务：问题评估，数据探索，数据预处理，模型训练、测试、部署，等等。下面你会看到这些核心步骤有用的的可视化展示：

![](https://cdn-images-1.medium.com/max/1000/1*KzmIUYPmxgEHhXX7SlbP4w.jpeg)

[UpX Academy](https://upxacademy.com/introduction-machine-learning/) 提供的典型机器学习工作流程核心步骤

理想的课程能够介绍完整的过程并提供交互式的例子、课后作业、小测试，学员们能自己体验到每个任务。

### 这些课程包含了深度学习吗？

首先咱们来定义一下深度学习。简洁点的定义是：

> “深度学习是机器学习的一个分支，关注的是受大脑结构和功能启发的人工神经网络算法。”

> — Jason Brownlee，来自[掌握机器学习](http://machinelearningmastery.com/what-is-deep-learning/)

可能你希望这样，我们的课程正好有一些包含了深度学习的内容。但我是没有选择那些只包含深度学习的课程的。如果你就是对深度学习感兴趣，我们建议你学习一下下面的[文章](https://medium.freecodecamp.com/dive-into-deep-learning-with-these-23-online-courses-bf247d289cc0)：

* [在线 12 课深入理解深度学习：每天都有关于深度学习如何改变我们周围世界的头条。几个例子：](https://medium.freecodecamp.com/dive-into-deep-learning-with-these-23-online-courses-bf247d289cc0 "https://medium.freecodecamp.com/dive-into-deep-learning-with-these-23-online-courses-bf247d289cc0")

列表里面我最推荐的 TOP 3 是：

*   [**使用 TensorFlow 编写深度学习创意应用**](https://www.class-central.com/mooc/6679/kadenze-creative-applications-of-deep-learning-with-tensorflow)， _Kadenze_
*   [**用于机器学习的神经网络**](https://www.class-central.com/mooc/398/coursera-neural-networks-for-machine-learning)， _多伦多大学 (Geoffrey Hinton执教) 发布于 Coursera_
*   [**深度学习 A-Z™：手把手教你写人工神经网络**](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fdeeplearning%2F)， _Kirill Eremenko，Hadelin de Ponteves 和 SuperDataScience Team 发布于 Udemy_

### 推荐的先决条件

下面列出的一些课程要求学员有编程、微积分、线性代数和统计学经验。鉴于机器学习是一门高级学科，这些先决条件是可以理解的。

有些科目不懂？好消息！其中一些经验可以通过我们在头两篇关于“数据科学生涯指导”的推荐文章（[编程](https://medium.freecodecamp.com/if-you-want-to-learn-data-science-start-with-one-of-these-programming-classes-fb694ffe780c#.ld31z08y5), [统计学](https://medium.freecodecamp.com/if-you-want-to-learn-data-science-take-a-few-of-these-statistics-classes-9bbabab098b9)）中学习到。下面的几个顶级课程还提供了简单的微积分和线性代数复习，并着重突出了与那些不太熟悉的机器学习最相关的方面。

### 我们甄选的最佳机器学习课程是……

*   [机器学习](https://www.class-central.com/mooc/835/coursera-machine-learning)，斯坦福大学发布于 Coursera

斯坦福大学发布在 Coursera 的[机器学习](https://www.class-central.com/mooc/835/coursera-machine-learning)在评分、评论和大纲匹配上是目前最明确的赢家。课程由著名的 Andrew Ng 讲授，他是 Google 大脑的创始人，[百度](https://en.wikipedia.org/wiki/Baidu)的前首席科学家。这是引发 Coursera 成立的课程。它通过 422 条评论得到 4.7 星的加权平均得分。

这门课程发布于 2011 年，涵盖了机器学习工作流程的所有方面。尽管它比自身基于的最初的斯坦福大学课程范围小了一点，依然成功包含了大量的技术和算法。预估的时间线是 7 周，包扩两周的神经网络和深度学习。课程还提供了免费版和收费版两种选择。

Ng 是一位有活力而又温柔的导师，而且经验丰富。他激励自信，尤其是在分享实际实施技巧和常见陷阱警告的时候。他帮助学员复习线性代数并强调与机器学习最相关的微积分知识。


评估是自动的，通过每节课后的多项选择测验和编程作业完成。这些作业（一共有八次）可以使用 MATLAB 或 Octave 完成，后者是 MATLAB 的一个开源版本。Ng 常解释他对语言的选择：

> 以前我总是尝试使用各种不同的语言讲授机器学习，包括 C++、Java、Python、NumPy，当然还有 Octave，等等。在我教了十年机器学习之后我发现使用 Octave 做为编程环境会让你学得最快。

尽管 Python 和 R 在 2017 年有着[上升的人气](http://blog.codeeval.com/codeevalblog/2016/2/2/most-popular-coding-languages-of-2016)，似乎更引人注目，评论家们注意到那不应该阻止你学习这门课。

一些着名评论家注意到以下内容：

> 作为 MOOC 世界中长期以来的知名课程，斯坦福大学的机器学习确实是这一主题的权威介绍。该课程广泛涵盖了机器学习的所有主要领域。Ng 教授在每个部分之前都有激励性的讨论和例子。

> Andrew Ng 是一位有天赋的老师，能够以相当直观清晰的方式解释复杂主题，包括概念后面的数学原理。强烈推荐！

> 我看这门课的唯一问题是，它是否为其他课程设置了太高的期望值。

![](https://cdn-images-1.medium.com/max/800/1*viCB-ayFFQi-4Fs_NYLVVQ.png)

* YouTube 视频链接：https://youtu.be/e0WKJLovaZg

Andrew Ng 的[机器学习](https://www.class-central.com/mooc/835/coursera-machine-learning)课程预览视频。

### 一门由杰出教授讲授的常春藤大学课程

*   [机器学习](https://www.class-central.com/mooc/7231/edx-machine-learning) （哥伦比亚大学发布于 edX ）

哥伦比亚大学的[机器学习](https://www.class-central.com/mooc/7231/edx-machine-learning)是他们发布在 edX 上的《人工智能微硕士》（ Artificial Intelligence MicroMasters ）课程的一个相当新的部分（_译者注：《微硕士》课程是由 edX 推出的一系列在线研究生课程，可以用来学习职业发展的独立技能或从各自大学获得研究生同等学力证书，相当于一个完整硕士学位的学期_）。 尽管它太新了还没有太多的评论，但是已有的评论却异常给力。授课教授 John Paisley 以杰出、授课简杰、聪明而闻名。这门课程通过它的10条评论加权平均得分 4.8 星。

这门课程覆盖了机器学习工作流程的全部方面，而且在算法上比上面的斯坦福课程还多。哥伦比亚的课程是更加高阶的入门课程，评论中有提到说学员需要很熟悉我们前面推荐的先决条件：微积分、线性代数、统计学、概率论和编程。

它的毕业评估由 11 次测验、4 次编程作业和期末考试组成。学员们可自行选择 Python、Octave 或 MATLAB 完成作业。课程的总预计时长是 12 周，每周 8 到 10 课时。 它是免费的，不过具有经过验证的学历证书可供购买。

下面是一些上面提到的高质量[评论](https://www.coursetalk.com/providers/edx/courses/machine-learning-5)：

> 在当学生的这些年，我经历了各种教授：不够杰出的教授、自身杰出但是授课能力一般的教授、杰出而又擅长授课的教授。Paisley 博士就属于第三种。

> 这门课太棒了！老师的语言太精准了，在我看来这也是这门课最突出的亮点之一。课程质量很高，PPT 也超棒。

> Paisley 博士和他的导师都是机器学习之父迈克尔·乔丹的学生。 Paisley 博士因为授课清晰成为哥伦比亚大学最好的 ML 教授。这个学期有将近 240 个学生选他的课，这个数字是哥伦比亚大学所有讲授机器学习的教授中最大的。

![](https://cdn-images-1.medium.com/max/800/1*q4Qa-kxC6MXFwct_9635ug.png)

* YouTube 视频链接：https://youtu.be/mANw77caYSI

哥伦比亚大学发布于 edX 的《微硕士》课程预览视频。[机器学习](https://www.class-central.com/mooc/7231/edx-machine-learning)课程简介开始于大约 1:00。

### 来自工业专家的 Python 和 R 实用简介

*   [机器学习 A-Z™：手把手教你用 Python 和 R 实战数据科学](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fmachinelearning%2F) （Kirill Eremenko，Hadelin de Ponteves 和 SuperDataScience Team 发布于 Udemy）

发布于 Udemy 的[机器学习 A-Z™](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fmachinelearning%2F) 是一门同时介绍了 Python 和 R 的无孔不入般详细的课程。这是罕见的，其他任何顶级课程也不会有这种评价。它的评论数是在我们推荐课程中最高的，高达 8119 条，得到 4.5 星的加权平均得分。

它覆盖了全部的机器学习工作流程，还通过 40.5 小时的按需视频教程提供了数量近乎荒谬（好的那种）的算法讲解。这门课比上面两门课更实用，数学要求也低。每个部分都以 Eremenko 的“直觉”视频开始，视频中总结了将被讲授的概念中的重要理论。然后 de Ponteves 会通过一些分开的视频讲述如何通过 Python 和 R 实现出来。

一个“加分项”是这门课程包含了 Python 和 R 的代码模版供学员下载以便在他们自己的项目中使用。课程也提供了测验和家庭作业挑战，不过不是这门课程的有理得分点。

Eremenko 和 SuperDataScience team 最受学员爱戴的是他们有能力“把复杂的事情搞简单”。此外，这门课程先决条件的要求也“只是一些高中数学”，所以对于被斯坦福和哥伦比亚课程难倒的学员可能是较好的选择。

一些突出的评论者[强调了](https://www.udemy.com/machinelearning/#reviews)以下内容：

> 这门课是专业出品，音质棒极了，释义也特别简洁清晰。你财力和时间的投资绝对有难以估量的回报。

> 在一门课中同时用两种语言学习简直太壮观了.

> Kirill 是 Udemy 上绝对最好的老师之一（如果不是在网上），我推荐他讲的所有课程。这门课有丰富的内容，丰富到爆！

![](https://cdn-images-1.medium.com/max/800/1*gl_KL2hhIkodQpznSzu8ZA.png)

* YouTube 视频链接：https://youtu.be/JbuYJTbmYEk

[机器学习 A-Z™](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fmachinelearning%2F)的预览视频。

### 比拼

我们的第一门甄选课程通过 422 条评论得到了 4.7 星的加权平均得分。我们看一下其他可选课程，以分值降序排列。再次提醒：纯粹深度学习的课程不包含在这篇指导里（那些课程可以在[这里](https://medium.freecodecamp.com/dive-into-deep-learning-with-these-23-online-courses-bf247d289cc0)查看）。

[《走近数据分析》](https://www.class-central.com/mooc/1623/edx-the-analytics-edge) （麻省理工学院于 edX）：更关注一般分析，虽然也有一些机器学习主题；使用 R 语言；使用我们熟悉的现实世界的例子进行强悍的表述；有挑战；12 周，每周 10 到 15 学时；可自愿购买经过认证的证书；有 214 条评论，加权平均得分 4.9 星。

* YouTube 视频链接：https://youtu.be/1BMSOBCe07k

这门麻省理工学院梦幻课程的推广视频：[走近数据分析](https://www.class-central.com/mooc/1623/edx-the-analytics-edge)。

[《数据科学和机器学习 Python 训练营》](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fpython-for-data-science-and-machine-learning-bootcamp%2F) （何塞波蒂利亚大学于 Udemy）：包含了完整数据科学流程的内容，有大块的机器学习内容；更详细的 Python 入门；优秀的课程，不过不在本文的理想教授范围；21.5 小时的按需视频；价格根据 Udemy 账户级别进行折扣，这在 Udemy 很常见；有 3316 条评论，加权平均得分 4.6 星。

[《数据科学和机器学习 R 训练营》](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fdata-science-and-machine-learning-bootcamp-with-r%2F)（何塞波蒂利亚大学于 Udemy）：上面对波蒂利亚大学课程的评价同样适用于此，只不过语言换成 R；17.5 小时的按需视频；价格根据 Udemy 账户级别进行折扣，这在 Udemy 很常见；有 1317 条评论，加权平均得分 4.6 星。

[《机器学习系列课程》](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fuser%2Flazy-programmer%2F)（(Lazy Programmer 公司于 Udemy）：由具有不凡工作经验的数据科学家、大数据工程师、全栈软件工程师讲授；Lazy Programmer 目前在 Udemy 有 16 门聚焦机器学习的课程；总体上看，课程由 5000+ 评分，基本都在 4.6 星以上；每门课的描述中都有一个有用的课程排序；价格根据 Udemy 账户级别进行折扣，这在 Udemy 很常见。

[《机器学习》](https://www.class-central.com/mooc/1020/udacity-machine-learning)（佐治亚理工学院于 Udacity）：三门独立课程组合而成：监督学习、无监督学习和强化学习；是该网站机器学习工程师 Nanodegree 和该校在线硕士学位（OMS）的一部分；信息量刚好可消化的视频大小正是 Udacity 的风格；友好的教授们；估计 4 个月可毕业；免费；9 条评论，4.56 星。

[《在 Azure HDInsight 中使用 Spark 实现预测分析》](https://www.class-central.com/mooc/4151/edx-implementing-predictive-analytics-with-spark-in-azure-hdinsight)（微软与 edX）：介绍了机器学习的核心概念和一些算法；利用了一些大数据友好的工具，包括 Apache Spark、 Scala 和 Hadoop；Python 和 R 都用到了；预计 6 周，每周 4 课时；可自愿购买经过认证的证书；有 6 条评论，4.5 星。

[《使用 Python 学习数据科学和机器学习：手把手教你！》](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fdata-science-and-machine-learning-with-python-hands-on%2F)（Frank Kane 于 Udemy）：使用 Python；Kane 在亚马逊公司和 IMDb有 9 年工作经验；价格根据 Udemy 账户级别进行折扣，这在 Udemy 很常见；有 4139 条评论，4.5 星。

[用于大数据和机器学习的 Scala 和 Spark 技术](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fscala-and-spark-for-big-data-and-machine-learning%2F)（何塞波蒂利亚大学于 Udemy）：关注“大数据”，尤其是使用 Scala 和 Spark 实现；10 小时的按需视频；价格根据 Udemy 账户级别进行折扣，这在 Udemy 很常见；607 条评论，4.5 星。

[机器学习工程师 Nanodegree](https://www.class-central.com/certificate/machine-learning-engineer-nanodegree--nd009)（Udacity）：Udacity 的旗舰机器学习课程，这种课程具有一流的项目评审系统和职业支持；该课程由几个都是免费的独立课程组成；与 Kaggle 联合创建；预计 6 个月学完；目前是每月 199 美元，12 个月之内毕业可享受 50% 的学费退款；2 条评论，4.5 星。

[《从数据中学习（机器学习介绍）》](https://www.class-central.com/mooc/1240/edx-learning-from-data-introductory-machine-learning)（加州理工学院于 edX）：课程报名当前在 edX 上关闭了，不过依然可以通过 CalTech 的独立平台报名（见下面）；42 条评论，4.49 星。

* YouTube 视频链接：https://youtu.be/KlP0DpiM7Lw

Caltech 和 Yaser Abu-Mostafa 的[从数据中学习](https://www.class-central.com/mooc/366/learning-from-data-introductory-machine-learning-course)介绍视频。

[《从数据中学习（机器学习介绍）》](https://www.class-central.com/mooc/366/learning-from-data-introductory-machine-learning-course)（Yaser Abu-Mostafa 于加州理工学院）：“真正的 Caltech 课程，不是阉割版”；评论强调它在理解机器学习理论上很优秀；Yaser Abu-Mostafa 教授在学生中很流行，还写了这门课使用的教科书；上传到油管的视频是上课录音（带有 PPT 的画中画功能），家庭作业是 PDF 文件；学生在线学习的课程体验并不如 TOP 3 推荐那么精彩；7条评论，4.43 星。

[《海量数据集挖掘》](https://www.class-central.com/mooc/2406/stanford-openedx-mining-massive-datasets)（斯坦福大学）：关注“大数据”的机器学习课程；介绍了现代分布式文件系统和 MapReduce；7 周，每周 10 小时；免费；30 条评论，4.4 星。

[《AWS 机器学习：使用 Python 的完整指导》](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Faws-machine-learning-a-complete-guide-with-python%2F)（Chandra Lingam 于 Udemy）：唯一关注基于云端的机器学习课程，尤其是 Amazon Web Service。使用 Python；9 小时按需视频；价格根据 Udemy 账户级别进行折扣，这在 Udemy 很常见；62 条评论，4.4 星。

[《机器学习介绍和使用 Python 进行面部识别》](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Fintroduction-to-machine-learning-in-python%2F)（Holczer Balazs 于 Udemy）：使用 Python；8 小时按需视频；价格根据 Udemy 账户级别进行折扣，这在 Udemy 很常见；162 条评论，4.4 星。

[《StatLearning：统计学习》](https://www.class-central.com/mooc/1579/stanford-openedx-statlearning-statistical-learning)（斯坦福大学）：基于超优秀的教科书[《统计学习入门，使用 R 程序》](https://www.amazon.com/Introduction-Statistical-Learning-Applications-Statistics-ebook/dp/B01IBM7790)并由编写书的教授上课；评论说 MOOC 引用了书中“薄弱”的练习和平庸的视频，没有书好；9 周，每周 5 课时；免费；84 条评论，4.35 星。

[《机器学习规范》](https://www.class-central.com/certificate/machine-learning-specialization)（华盛顿大学于 Coursera）：超棒的课程，可惜最后两课（包括顶点课程）被删掉了（_译者注：顶点课程是美国大学开设在实用性很强的专业中让学生整合所学领域的知识并充分利用的课程_）；评论说该系列课程比那些顶级机器学习课程 —— 也就是斯坦福和 Caltech 的 —— 更容易消化（对那些没有很强工科背景的学员来说）；记住该课程在推荐系统和深度学习上并不完整，还缺少课程总结；有免费和收费版本；80 条评论，4.31 星。

![](https://cdn-images-1.medium.com/max/1000/1*fgFqV9nyUKHi7txzgKcW4w.png)

Coursera 上华盛顿大学正在上这门[《机器学习规范》](https://www.class-central.com/certificate/machine-learning-specialization)。

[《从 0 到 1：机器学习和NLP，使用 Python 切入正题》](https://click.linksynergy.com/fs-bin/click?id=SAyYsTvLiGQ&subid=&offerid=323058.1&type=10&u1=medium-career-guide-machine-learning&tmpid=14538&RD_PARM1=https%3A%2F%2Fwww.udemy.com%2Ffrom-0-1-machine-learning%2F)（Loony Corn 于 Udemy）：“一种脚踏实地，害羞但自信的机器学习技巧”；由具有数十年工业经验的四人小组授课；使用 Python；价格根据 Udemy 账户级别进行折扣，这在 Udemy 很常见；494 条评论，4.2 星。

[《机器学习的原则》](https://www.class-central.com/mooc/6511/edx-principles-of-machine-learning)（微软于 edX）：使用 R、Python 和 微软 Azure 机器学习工具；是微软数据科学专业课程认证的一部分；6 周，每周 3 - 4 小时；可自愿购买经过认证的证书；11 条评论，4.09 星。

[《大数据：统计推断与机器学习》](https://www.class-central.com/mooc/5421/futurelearn-big-data-statistical-inference-and-machine-learning)（昆士兰科技大学于 FutureLearn）：一门聚焦于大数据、漂亮而又简洁的机器学习探索课程；覆盖了诸如 R、H20 流和 WEKA 等工具；推荐三周就学完，每周 2 课时；有免费和收费版本；4 条评论，4 星。

[《基因组数据科学与聚类》](https://www.class-central.com/mooc/3556/coursera-genomic-data-science-and-clustering-bioinformatics-v)（生物信息学第五部）（加利福尼亚大学和 San Diego 于 Coursera）：面向对计算机科学和生物学的交叉学科感兴趣的人，并展示这门交叉学科如何代表现代科学的重要前沿；关注聚类和数据降维；加州大学圣地亚哥分校（UCSD）生物信息学专业的一部分；有免费和收费版本；3 条评论，4 星。

[《机器学习简介》](https://www.class-central.com/mooc/2996/udacity-intro-to-machine-learning)（Udacity）：在深度和理论上优先考虑学习宽度和实用工具主题（使用 Python）；两位老师 —— Sebastian Thrun 和 Katie Malone —— 让课程充满趣味；课程视频是刚好能够消化的大小；每节课的小项目后面都有测验；目前是 Udacity 数据分析师纳学位的一部分（_译者注：纳学位，或者说 Nanodegree，是优达学院和企业推出的系列联合认证课程,一般可在 12 个月内结业。“纳”模仿自“微学院”中的“微”，都表示模仿自高校。“纳”和“微”都是度量单位，“纳”比“微”更小_）；估计 10 周；免费；19 条评论，3.95 星。

* YouTube 视频链接：https://youtu.be/lL16AQItG1g

Sebastian Thrun 和 Katie Malone 讲授的 Udacity [《机器学习简介》](https://www.class-central.com/mooc/2996/udacity-intro-to-machine-learning)介绍视频。

[《用于数据分析的机器学习》](https://www.class-central.com/mooc/4354/coursera-machine-learning-for-data-analysis)（卫斯理大学于 Coursera）：对机器学习及几个选择算法的简单介绍；覆盖决策树、随机森林、LASSO 回归和 K 均值聚类；是卫斯理大学数据分析和解释专业的一部分；估计 4 周；有免费和付费版本；5 条评论，3.6 星。

[《数据科学：使用 Python 编程》](https://www.class-central.com/mooc/6471/edx-programming-with-python-for-data-science)（微软于 edX）：微软和 Coding Pojo 联合出品；使用 Python；6 周，每周 8 小时；有免费和付费版本；37 条评论，3.46 星。

[《用于交易的机器学习》](https://www.class-central.com/mooc/1026/udacity-machine-learning-for-trading)（佐治亚科技大学于 Udacity）：专注于将概率机器学习方法应用于交易决策；使用 Python；是 Udacity 机器学习工程师纳学位和佐治亚科大在线硕士学位（OMS）的一部分；估计 4 个月；免费；14 条评论，3.29 星。

[《实用机器学习》](https://www.class-central.com/mooc/1719/coursera-practical-machine-learning)（约翰霍普金斯大学于 Coursera）：简洁、实用的介绍了一些机器学习算法；一些一星二星的评论表达了对课程的各种担忧；是该校数据科学专业的一部分；4周，每周 4 - 9 小时；有免费和收费版本；37 条评论，3.11 星。

[《用于数据科学和数据分析的机器学习》](https://www.class-central.com/mooc/4912/edx-machine-learning-for-data-science-and-analytics)（哥伦比亚大学于 edX）：介绍了机器学习的广泛主题；一些负面评论对课程内容的选择、缺少编程作业和缺乏有灵感的展示提出了担忧；超过 5 周，每周 7 - 10 小时；36 条评论，2.74 星。

[《推荐系统规范》](https://www.coursera.org/specializations/recommender-systems)（明尼苏达大学于 Cou）：重点关注了一种特定的机器学习类型 —— 推荐系统；4 节专业课加一节顶点课程，这是一个案例研究；使用 LensKit（推荐系统的一个开源工具集） 上课；有免费和收费版本；2 条评论，2 星。

[《使用大数据进行机器学习》](https://www.class-central.com/mooc/4238/coursera-machine-learning-with-big-data)（加利福尼亚大学和 San Diego 于 Coursera）：严重负面的评论突出了课程糟糕的教学和评估；一些评论说完成整个课程只需要几小时；是该校大数据专业的一部分；有免费和收费版本；14 条评论，1.86 星。

[《实用预测分析：模型和方法》](https://www.class-central.com/mooc/4341/coursera-practical-predictive-analytics-models-and-methods)（华盛顿大学于 Coursera）：对机器学习的核心概念进行了简单介绍；有条评论说课程没有测验，作业也没有挑战；是该校数据科学扩展专业的一部分；超过 4 周，每周 6 - 8 小时；有免费和收费版本；4 条评论，1.75 星。

下面的课程截止到 2017 年 5 月还没有或只有一条评论。

[Machine Learning for Musicians and Artists](https://www.class-central.com/mooc/3768/kadenze-machine-learning-for-musicians-and-artists) (Goldsmiths, University of London/Kadenze): Unique. Students learn algorithms, software tools, and machine learning best practices to make sense of human gesture, musical audio, and other real-time data. Seven sessions in length. Audit (free) and premium ($10 USD per month) options available. It has one 5-star review.

* YouTube 视频链接：https://youtu.be/pSnRmBt0pXI

The promo video for Goldsmiths, University of London’s [Machine Learning for Musicians and Artists](https://www.class-central.com/mooc/3768/kadenze-machine-learning-for-musicians-and-artists) on Kadenze.

[Applied Machine Learning in Python](https://www.class-central.com/mooc/6673/coursera-applied-machine-learning-in-python) (University of Michigan/Coursera): Taught using Python and the scikit learn toolkit. Part of the Applied Data Science with Python Specialization. Scheduled to start May 29th. Free and paid options available.

[Applied Machine Learning](https://www.class-central.com/mooc/6406/edx-applied-machine-learning) (Microsoft/edX): Taught using various tools, including Python, R, and Microsoft Azure Machine Learning (note: Microsoft produces the course). Includes hands-on labs to reinforce the lecture content. Three to four hours per week over six weeks. Free with a verified certificate available for purchase.

[Machine Learning with Python](https://bigdatauniversity.com/courses/machine-learning-with-python/) (Big Data University): Taught using Python. Targeted towards beginners. Estimated completion time of four hours. Big Data University is affiliated with IBM. Free.

[Machine Learning with Apache SystemML](https://bigdatauniversity.com/courses/machine-learning-apache-systemml/) (Big Data University): Taught using Apache SystemML, which is a declarative style language designed for large-scale machine learning. Estimated completion time of eight hours. Big Data University is affiliated with IBM. Free.

[Machine Learning for Data Science](https://www.class-central.com/mooc/8216/edx-machine-learning-for-data-science) (University of California, San Diego/edX): Doesn’t launch until January 2018. Programming examples and assignments are in Python, using Jupyter notebooks. Eight hours per week over ten weeks. Free with a verified certificate available for purchase.

[Introduction to Analytics Modeling](https://www.class-central.com/mooc/8217/edx-introduction-to-analytics-modeling) (Georgia Tech/edX): The course advertises R as its primary programming tool. Five to ten hours per week over ten weeks. Free with a verified certificate available for purchase.

[Predictive Analytics: Gaining Insights from Big Data](https://www.class-central.com/mooc/7645/futurelearn-predictive-analytics-gaining-insights-from-big-data) (Queensland University of Technology/FutureLearn): Brief overview of a few algorithms. Uses Hewlett Packard Enterprise’s Vertica Analytics platform as an applied tool. Start date to be announced. Two hours per week over four weeks. Free with a Certificate of Achievement available for purchase.

[Introducción al Machine Learning](https://miriadax.net/web/introduccion-al-machine-learning) (Universitas Telefónica/Miríada X): Taught in Spanish. An introduction to machine learning that covers supervised and unsupervised learning. A total of twenty estimated hours over four weeks.

[Machine Learning Path Step](https://www.dataquest.io/path-step/machine-learning) (Dataquest): Taught in Python using Dataquest’s interactive in-browser platform. Multiple guided projects and a “plus” project where you build your own machine learning system using your own data. Subscription required.

* * *

The following six courses are offered by [DataCamp](https://www.datacamp.com/courses/topic:machine_learning?tap_a=5644-dce66f&tap_s=93618-a68c98). DataCamp’s hybrid teaching style leverages video and text-based instruction with lots of examples through an in-browser code editor. A subscription is required for full access to each course.

![](https://cdn-images-1.medium.com/max/1000/1*eRUPgszpDHzEUpvXhFMeUg.png)

[DataCamp](https://www.datacamp.com/courses/topic:machine_learning?tap_a=5644-dce66f&tap_s=93618-a68c98) offers several machine learning courses.

[Introduction to Machine Learning](https://www.datacamp.com/courses/introduction-to-machine-learning-with-r?tap_a=5644-dce66f&tap_s=93618-a68c98) (DataCamp): Covers classification, regression, and clustering algorithms. Uses R. Fifteen videos and 81 exercises with an estimated timeline of six hours.

[Supervised Learning with scikit-learn](https://www.datacamp.com/courses/supervised-learning-with-scikit-learn?tap_a=5644-dce66f&tap_s=93618-a68c98) (DataCamp): Uses Python and scikit-learn. Covers classification and regression algorithms. Seventeen videos and 54 exercises with an estimated timeline of four hours.

[Unsupervised Learning in R](https://www.datacamp.com/courses/unsupervised-learning-in-r?tap_a=5644-dce66f&tap_s=93618-a68c98) (DataCamp): Provides a basic introduction to clustering and dimensionality reduction in R. Sixteen videos and 49 exercises with an estimated timeline of four hours.

[Machine Learning Toolbox](https://www.datacamp.com/courses/machine-learning-toolbox?tap_a=5644-dce66f&tap_s=93618-a68c98) (DataCamp): Teaches the “big ideas” in machine learning. Uses R. 24 videos and 88 exercises with an estimated timeline of four hours.

[Machine Learning with the Experts: School Budgets](https://www.datacamp.com/courses/machine-learning-with-the-experts-school-budgets?tap_a=5644-dce66f&tap_s=93618-a68c98) (DataCamp): A case study from a machine learning competition on DrivenData. Involves building a model to automatically classify items in a school’s budget. DataCamp’s “Supervised Learning with scikit-learn” is a prerequisite. Fifteen videos and 51 exercises with an estimated timeline of four hours.

[Unsupervised Learning in Python](https://www.datacamp.com/courses/unsupervised-learning-in-python?tap_a=5644-dce66f&tap_s=93618-a68c98) (DataCamp): Covers a variety of unsupervised learning algorithms using Python, scikit-learn, and scipy. The course ends with students building a recommender system to recommend popular musical artists. Thirteen videos and 52 exercises with an estimated timeline of four hours.

* * *

[Machine Learning](http://www.cs.cmu.edu/~ninamf/courses/601sp15/index.html) (Tom Mitchell/Carnegie Mellon University): Carnegie Mellon’s graduate introductory machine learning course. A prerequisite to their second graduate level course, “Statistical Machine Learning.” Taped university lectures with practice problems, homework assignments, and a midterm (all with solutions) posted online. A [2011 version](http://www.cs.cmu.edu/~tom/10701_sp11/) of the course also exists. CMU is one of the best graduate schools for studying machine learning and has a whole department dedicated to ML. Free.

[Statistical Machine Learning](https://www.class-central.com/mooc/8509/statistical-machine-learning) (Larry Wasserman/Carnegie Mellon University): Likely the most advanced course in this guide. A follow-up to Carnegie Mellon’s Machine Learning course. Taped university lectures with practice problems, homework assignments, and a midterm (all with solutions) posted online. Free.

![](https://cdn-images-1.medium.com/max/1000/1*umqMeqC5Ch-kR1i4hPBTrw.png)

CMU is one of the best grad schools for studying machine learning. [Machine Learning](http://www.cs.cmu.edu/~ninamf/courses/601sp15/index.html) and [Statistical Machine Learning](https://www.class-central.com/mooc/8509/statistical-machine-learning) are available online for free.

[Undergraduate Machine Learning](http://www.cs.ubc.ca/~nando/340-2012/index.php) (Nando de Freitas/University of British Columbia): An undergraduate machine learning course. Lectures are filmed and put on YouTube with the slides posted on the course website. The course assignments are posted as well (no solutions, though). de Freitas is now a full-time professor at the University of Oxford and receives praise for his teaching abilities in various forums. Graduate version available (see below).

[Machine Learning](http://www.cs.ubc.ca/~nando/540-2013/lectures.html) (Nando de Freitas/University of British Columbia): A graduate machine learning course. The comments in de Freitas’ undergraduate course (above) apply here as well.

### 要结束了

这是我们推荐最好在线课程来让你步入数据科学领域的六部分中的第五部分。我们的[第一部分](https://medium.freecodecamp.com/if-you-want-to-learn-data-science-start-with-one-of-these-programming-classes-fb694ffe780c#.fhrn45v3c)涵盖了编程课程，[第二部分](https://medium.freecodecamp.com/if-you-want-to-learn-data-science-take-a-few-of-these-statistics-classes-9bbabab098b9#.p7pac546r)是概率统计，[第三部分](https://medium.freecodecamp.com/i-ranked-all-the-best-data-science-intro-courses-based-on-thousands-of-data-points-db5dc7e3eb8e)是数据科学入门，[第四部分](https://medium.freecodecamp.com/an-overview-of-every-data-visualization-course-on-the-internet-9ccf24ea9c9b)是数据可视化。

* [**我基于数千个数据点对网络上的所有数据科学入门课程进行了排名：一年以前，我退出了加拿大最好的计算机科学课程之一。](https://medium.freecodecamp.com/i-ranked-all-the-best-data-science-intro-courses-based-on-thousands-of-data-points-db5dc7e3eb8e "https://medium.freecodecamp.com/i-ranked-all-the-best-data-science-intro-courses-based-on-thousands-of-data-points-db5dc7e3eb8e")

最后一部分将会是前面部分的总结，加上其他主题的最好课程，如数据整理、数据库，甚至还有软件工程。

如果你在寻找数据科学在线课程的完整列表，可以来 Class Central 的[数据科学和大数据](https://www.class-central.com/subject/data-science)主题页面。

如果你读完了还欲罢不能，可以看一下 [Class Central](https://www.class-central.com/) 的其他主题：

* [**这里有 250 所常春藤联盟高校的在线课程现在**：250 门 MOOC 课程包括布朗大学、哥伦比亚大学、康内尔大学、达特茅斯大学、哈佛大学、b宾夕法尼亚大学、普林斯顿大学和耶鲁大学。](https://medium.freecodecamp.com/ivy-league-free-online-courses-a0d7ae675869 "https://medium.freecodecamp.com/ivy-league-free-online-courses-a0d7ae675869")

* [**根据数据统计的 50 门最好的免费在线大学课程**：当我 2011 年十一月初创 Class Central 的时候只有大约 18 门免费在线课程，几乎都来自斯坦福大学。](https://medium.freecodecamp.com/the-data-dont-lie-here-are-the-50-best-free-online-university-courses-of-all-time-b2d9a64edfac "https://medium.freecodecamp.com/the-data-dont-lie-here-are-the-50-best-free-online-university-courses-of-all-time-b2d9a64edfac")

如果你对我遗漏的课程由提议，请回复我让我知道！

如果你觉得有帮助，点击 💚 会让更多 Medium 板块的用户看到本文。

_本文是我发布在 Class Central 的_[_原始文章_](https://www.class-central.com/report/best-machine-learning-courses/)_的缩减版，原文包含了详细的课程介绍。_

> 如果发现译文存在错误或其他需要改进的地方，欢迎到 [掘金翻译计划](https://github.com/xitu/gold-miner) 对译文进行修改并 PR，也可获得相应奖励积分。文章开头的 **本文永久链接** 即为本文在 GitHub 上的 MarkDown 链接。


---

> [掘金翻译计划](https://github.com/xitu/gold-miner) 是一个翻译优质互联网技术文章的社区，文章来源为 [掘金](https://juejin.im) 上的英文分享文章。内容覆盖 [Android](https://github.com/xitu/gold-miner#android)、[iOS](https://github.com/xitu/gold-miner#ios)、[前端](https://github.com/xitu/gold-miner#前端)、[后端](https://github.com/xitu/gold-miner#后端)、[区块链](https://github.com/xitu/gold-miner#区块链)、[产品](https://github.com/xitu/gold-miner#产品)、[设计](https://github.com/xitu/gold-miner#设计)、[人工智能](https://github.com/xitu/gold-miner#人工智能)等领域，想要查看更多优质译文请持续关注 [掘金翻译计划](https://github.com/xitu/gold-miner)、[官方微博](http://weibo.com/juejinfanyi)、[知乎专栏](https://zhuanlan.zhihu.com/juejinfanyi)。
