# 摘要：

####   	近年来BBS论坛已成为大学内相互沟通与学习交流的常用工具。它提供一块公共电子白板，每个用户都可以在上面书写，可发布信息或提出看法。用户在BBS站点上可以获得各种信息服务，发布信息，进行讨论，聊天等等。

####  	 本文讨论了一个网络BBS 的设计与实现过程，详细地讲述了开发一个基于Web 的BBS 网站系统所涉及到的技术和方法。系统采用jsp、servlet、mysql等技术，使用java语言编写。全文共分为介绍、收集背景资料、提案的组成部分、执行总结、需求陈述、项目描述、预算、组织信息、技术方案、结论。

------

# 正文：

#### 1.1系统目标 

#####    	本项目的开发是以web工程课程为契机，以实现文章的成功发表，留言的发布与回复为总任务，做成一类似BBS论坛的方式，达到用户之间信息交流的目的。本系统主要面对西电学生，故名“西电新鲜事”。用户可以先进行注册然后在主页面查看所有消息，进行发表文章，点赞，取消点赞，评论等操作。

#### 1.2项目的目的与意义

#####   1.交流的好工具

##### 	BBS论坛具有实时性、开放性和灵活的交互性等特点。因此BBS论坛同学之间交互和沟通的途径。在BBS论坛里的讨论者大部分学生，我们的目标是搭建一分享西电新鲜事的平台，把这作为信息传播的重要途径。分享糗闻囧事，点赞评论；提供更多的学习信息，进行学术上的思想交流。

#####   2.促进协作学习

#####	网络的论坛社区也是各种学习资源组合的场所，为学习者提供了学习环境。作为一个学生参与论坛的网络活动可包括许多种学习的意义，在特定板块内，论坛参与者围绕某个话题或者问题，通过发表、回复话题、版面讨论、站内信件等方式进行互动讨论、相互探讨，形成了一种以学习者为中心的学习方式。从教育网内人气排名前十名的论坛的网友参与的情况来看，在各大学习板块里，基本上每张帖子提出的问题都可以得到网友友好的、认真的回复解答，有着浓郁的协作探讨的学习气氛和良好的学习效果。
