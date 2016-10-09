---
layout: post
title: 北京儿童医院挂号App
date: 2015-02-06
thumb: https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 icon.png?raw=true
categories: development work
tags: home work office coding design
---

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 toutu.png?raw=true)

​                  

**项目背景**

作为全国规模最大最权威的综合性儿科医院，北京儿童医院每天都人满为患，虽然已经有了用于挂号的手机App，但由于其在功能和体验上不能满足广大家长的要求，遂院方希望重新设计一款手机App，并加大推广力度，取代费时费力的现场挂号制度，减轻院方压力，也为广大家长和患儿提供方便。

​                        

**我的角色**

参与用户调研，并负责整个项目的交互设计。 

​          

**痛点**

接到项目需求后，用研同事到医院进行了实地走访，了解就诊的流程中的实际情况，并邀请7位家长进行了电话访谈。下图为访谈总结的就医过程体验：

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 diaoyan.png?raw=true)

可以看出在挂号、候诊及检查阶段的体验较差，所以将提升这几个阶段的体验作为设计的重点。

​            

**挂号细节**

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 挂号1.png?raw=true) 

​                                                 ![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 挂号2.png?raw=true)

​                            

**候诊**

候诊过程中很多家长担心孩子在医院停留时间太长会感染其它疾病，最好在院外等候时也能了解候诊情况。

这个情景和等候用餐很相似，所以可借鉴已广泛用于餐厅等位的App排号功能：

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 候诊1.png?raw=true)

排号功能一般采用下拉刷新的方式来查询进度，但考虑到医院系统承受不住大规模的查询，所以使用了点击按钮刷新的方式。

​             

**检查**

检查的过程中涉及的流程更为复杂，检查的项目不同，流程也有所差异，且一次可能检查多个项目，为了明确信息采用了卡片的形式，每个卡片代表一个检查项目，将流程变为可视的步骤，且可通过App进行操作。根据就诊过程卡片的状态可分为如下几种：

​              

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 就诊.png?raw=true)

​               

其中根据是否可以当天进行检查、是否需排队、是否需取检等细分为不同流程。

​                    

**输出**

因为项目时间紧张，为了加快输出速度尝试了在制作页面时可直接生成跳转demo的原型工具。demo示例：

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 demo.gif?raw=true)

​                

**引导**

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 引导.png?raw=true)

​                                              

**总结**

![](https://github.com/wmyydi/wmyydi.github.io/blob/master/background/1 对比.gif?raw=true)

一期上线一段时间后，医院取消了窗口挂号，希望这个产品可以帮助到苦于挂号的家长们。虽然有功能这一期没有上线，也没机会再做优化，但是会总结经验在以后做得更好。



​                 
