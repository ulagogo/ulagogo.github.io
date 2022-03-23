---
title: 手游发行平台 
date: 2022-03-20 
categories: ["work"] 
tags:
    - 手游渠道发行
    - SAAS
    - B端设计
---

——协助手游发行的全流程  

用户路径：  
![](https://tva1.sinaimg.cn/large/e6c9d24ely1h0k5dbqzmrj21840cwwfg.jpg)  

1. 游戏排期日历设计：  
![](https://tva1.sinaimg.cn/large/e6c9d24ely1h0k65w2ua0j21980ozn0r.jpg)    
除了视图和布局的不合理，旧版日历也存在可简化操作路径的功能。如，筛选更新类型时，需要下拉选择后再次点搜索按钮才能生效，取消也需要再次点击按钮；日期切换涉及到两个下拉列表分别控制年和月的切换；新增计划事件时，即使只有少量选项也使用下拉菜单进行选择操作。  

新版日历优化，将页面分为月视图和日视图展示：    
- 月视图：以事件优先级进行颜色区分，以突出重要事件。标签以icon区分游戏，文本展示用户所添加的事件标题，将有限的标签空间展示最有效的信息。日历中可展示有时间跨度的事件，提高了日历使用的灵活性和自由度。 
- 日视图：初始默认展示今日所有事件，可点击日历区域进行日期的切换。
![](https://tva1.sinaimg.cn/large/e6c9d24ely1h0k5yx0jfqg21440sp0z3.gif)  

2. 本地打包工具设计：  
可进行多任务的选择和配置，展示每个渠道的配置状态标识。配置卡片可进行收起，因此可在同一页面对所有渠道进行配置。  
![](https://tva1.sinaimg.cn/large/e6c9d24ely1h0k6mgpgcsj20tf0kxwg6.jpg)  

3. 推送功能设计：  
为满足玩家回流需求所设计的新全球推送功能。  

- 任务列表：  
任务列表设计的主要难点在于一次任务中可以有多个“子任务”，即可选循环或定时的多次推送。在列表对于推送时间和结果的展示上做了如下处理：  
![](https://tva1.sinaimg.cn/large/e6c9d24ely1h0k6isfdltj20yi0mjack.jpg)  

- 推送任务:  
支持多个可选择的筛选项， 包括安卓和iOS平台的选择、推送次数类型（多次推送则涉及到多次时间或时间段的选择），在表单中对于推送的类型和目标做了如下处理：
![](https://tva1.sinaimg.cn/large/e6c9d24ely1h0k6jm29lcj20u00yhwhk.jpg) 

- 任务详情：
![](https://tva1.sinaimg.cn/large/e6c9d24ely1h0k6jx7pghj20kx0r1jt5.jpg)  

4. 版本更新说明弹窗设计：  
![](https://tva1.sinaimg.cn/large/e6c9d24ely1h0k5940bebj20ul0nf0uy.jpg)