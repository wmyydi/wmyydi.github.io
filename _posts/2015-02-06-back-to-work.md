---
layout: post
title: 北京儿童医院挂号App
date: 2015-02-06
thumb: https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 icon.png?raw=true
categories: development work
tags: home work office coding design
---

​              

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 toutu.png?raw=true)



**项目背景**

相信大多数人生病时都会抱怨：去医院挂号实在太困难！特别是有孩子的家长们，不仅去医院的频率更高，挂号的心情也更急切。作为全国规模最大最权威的综合性儿科医院，北京儿童医院每天都人满为患，虽然已经有了用于挂号的手机App，但由于其在功能和体验上不能满足广大家长的要求，选择来现场挂号的人还是占大多数，遂院方希望重新设计一款手机App，并加大推广力度，取代费时费力的现场挂号制度，减轻院方压力，也为广大家长和患儿提供方便。

​          

**我的角色**

参与用户调研，根据调研结果确定功能、负责整个项目的交互设计及输出 

​          

**痛点**

接到项目需求后，用研同事到医院进行了实地走访，了解就诊的流程中的实际情况，并邀请7位家长进行了电话访谈。下图为访谈总结的就医过程体验

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 diaoyan.png?raw=true)

可以看出在挂号、候诊及检查阶段的体验较差，通过使用App可以解决挂号排队的问题，那么另外两个来提升这几个阶段的体验呢？

​            

**挂号**

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 挂号1.png?raw=true) 

​                                                 ![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 挂号2.png?raw=true)

​              

**候诊**

候诊过程中家长比较担心的是：儿童的抵抗力比较弱，与很多患儿长时间处于相同的空间内，会不会感染其它疾病。有家长表示会至少两个人一起陪孩子去医院，一个负责排队，一个带孩子到医院附近等待。家长的顾虑不无道理，但也加重了看病的负担。如果把候诊比喻成等候用餐的话，马上就能联想到已广泛用于餐厅等位的App排号功能，为何不把它应用到候诊的情景下呢：

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 候诊1.png?raw=true)

排号功能一般采用下拉刷新的方式来查询进度，但考虑到医院系统承受不住大规模的查询，所以使用了点击按钮刷新的方式。

​             

**检查**

检查的过程中涉及的流程更为复杂，检查的项目不同，流程也有所差异，且一次可能检查多个项目，为了明确信息采用了卡片的形式，每个卡片代表一个检查项目，将流程变为可视的步骤，且可通过App进行操作。根据就诊过程卡片的状态可分为如下几种：

​              

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 就诊.png?raw=true)

​               

其中根据是否可以当天进行检查、是否需排队、是否需要取检等等可根据项目不同细分为不同流程。

​               

**总结**

这个项目一期上线时上线时与同事去儿童医院进行了后期支持，我在建卡大厅呆了两天的时间，原本是为了解答关于新上线App的问题，到后来无论问我些什么也大都回答得上了。

早晨6点医院门口早已排起了长队，进入医院后还要等待7点才能开始挂号，整个大厅挤满了人，只有亲身经历才知道挂号的艰难。

上线那天因为兼容性还有新旧系统对接出了不少问题，也发现了一些设计上的不足，但没有机会再去改进了，因为开发和工期的原因没有上线的模块也不知道还会不会上线，总有很多遗憾，我能做得就是总结经验，希望下个项目会做得更好。

​                 
