---
title: "《毕业设计文档》《毕业论文文档》择一"
excerpt_separator: "<!--more-->"
categories:
  - 毕业
tags:
  - 开题
image: 
  path: /assets/imgs/xkcd-girls-math.gif
  thumbnail: /assets/imgs/xkcd-girls-math.gif
  caption: "开题报告格式简要说明"
---


<!--more-->

<script src='https://unpkg.com/mermaid@8.4.2/dist/mermaid.min.js'></script>
<script>mermaid.initialize({startOnLoad:true});</script>


# 顶点课程/毕业设计/论文开题报告提纲

* 论文题目：
* 姓名：


## 设计/论文题亮点

* [[M]]使用的方法数据：具体数字/时间的文档分析丶平台界面分析丶访谈丶文献丶调研丶焦点团体丶设计工作坊丶A/B测试丶等
* [[A]]产出的专业建构物：具体文档丶图表丶产品原型丶等
* [[C]]立基的概念出发点：(设计思维系列) 用户体验丶可用性丶设计思维；(平台/系统思维系列)核心交互丶网络效应丶模块化丶平台生态系丶竞争及策略丶系统思维；(其它设计理念系列)

 说明：量力而为，以两门3学分课的期末项目的量来估工作量，要抓要害而非假大空

 若师生未能有共识，建议以学生先选取网新专业之核心课及方向课2门课为主的内容及项目为基底来思考课题方向


## 一丶选题意义
### 1丶理论意义

(一句话总结[[C]]立基的概念出发点如何能因本研究而有所新应用或新知识的产出，特别是基於[[M]]使用的方法数据)

### 2丶现实意义

(一句话总结[[A]]产出的专业建构物如何能因本研究而有所新的现实意义，特别是基於[[M]]使用的方法数据)


 说明：意义主要是指外部重要性(external centrality)，假定真的做完了, 对谁有什麽样的启发及启示？对公司省成本？对公司增加营收？对领导增加全局观的决策方法？对学者及政策制定者总结最新知识？

 若师生未能有共识，建议以学生先选取网新专业之核心课及方向课2门课为主的内容及项目为基底来思考课题方向



## 二丶中英文摘要与关键词
 关键词：关键词是供检索用的主题词条，应采用能覆盖设计（论文）主要内容的通用技术词条（参照相应的技术术语标准）。关键词一般为3～5个，按词条的外延层次排列（外延大的排在前面）。

### 摘要
 中英文摘要：摘要应概括反映出毕业设计(论文)的内容丶方法丶成果和结论。摘要中不宜使用公式丶图表，不标注引用文献编号。中文摘要一般500字左右
 
### Abstract

 英文摘要内容应与中文摘要相对应。

### 关键词

 为了便于文献检索，应在摘要下方另起一行注明论文的关键词。


## 三丶文献综述

### 1丶[[C]]理论及[[A]]专业建构物演进过程及[[M]]使用的方法数据
(1-2句话总结3-4来源内容)
### 2丶国外研究综述
(1-2句话总结3-4来源内容)
### 3丶国内研究综述
(1-2句话总结3-4来源内容)
### 4丶本人对以上综述的评价
(1-2句话总结3-4来源内容)

 说明：开题时需要10篇引用文献，建议上述1-3每项只要一句话总结各3-4来源内容就可以


## 四丶参考文献

 中文文档及文献书写格式要按国家标准GB/7714－87或ACM SIGCHI格式规定，英文文档及文献要按APA或ACM SIGCHI格式规定。务必要设置好Zotero及Word Plugin。


## 五丶研究条件和可能存在的问题
 说明：学生自我评估，若没问题而被教师提问发现有重大研究条件及问题者，需要进行协助同学解决问题的社会服务。

## 六丶进度安排
 说明：管理好时间和任务乃重要应用能力，必需要有优先级排序丶串行和并行。必需要有合理的[甘特图](https://www.mindtheproduct.com/tame-your-roadmap/)

 工具建议：[Mermaidjs](https://mermaidjs.github.io/mermaid-live-editor/)可下载SVG
 
<div class="mermaid" style="background-color:lightgreen;"> 
gantt
       dateFormat  YYYY-MM-DD
       title 顶点课程进度安排-甘特图

       section 顶点课程
       已完成选题                :done,    des1, 2019-10-20,2019-11-27
       提案文档报告proposal      :active,  des2, 2019-11-27, 7d
       文档写作-期中前                  :         des3, after des2, 28d
       ◆期中进度审核打分         :         des4, after des3, 7d
       研究/放假活动             :         des5, after des4, 35d
       文档写作-期中后         :         des6, after des5, 42d
       ◆文档写作-全文提交(TBA待定):         des7, after des6, 7d

       section 关键任务
       选题完成                  :crit, done, after des1, 7d
       Github提案文档proposal    :crit, active, 2019-11-27,6d
       ◆研究/设计发问-方法-数据关系查核  :crit, 1d
       (一章)研究/设计发问       :crit, active, 2019-12-04,6d
       ◆方法-数据 可操作性完成查核       :crit, 1d
       (一章)方法-数据           :crit, active, 2019-12-11,13d
       ◆文献回顾-预期贡献/创新完成查核     :crit, 1d
       (一章)文献回顾           :crit, active, 2019-12-25,13d
       ◆期中进度审核打分                   :1d

       section 研究/放假活动
       研究                     :crit, after des4, 35d
       放假                     :      vac1, after des4, 35d

       section 文档写作
       ◆主要发现1节              : finding1, after des5, 14d
       ◆主要发现1节              : finding2, after finding1, 14d
       ◆主要发现1节              : finding3, after finding2, 14d
       ◆论文文稿互审             : peerreview, after finding3, 14d
       ◆文档写作-全文提交(TBA待定):    des7, after peerreview, 7d


</div>