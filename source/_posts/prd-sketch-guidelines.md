---
title: sketch产品设计规范
date: 2017-04-10 20:30:59
tags:
	- Guidelines
	- PM
	- UI
	- UX
categories: 产品部门
---

# 文件命名规则

## 文件命名规范：产品名称+Sys_更新功能_负责人

- TryOn: 营销互动系统（在线试戴系统）
- Bonus: 红包兑换系统
- Store: 门店系统
- Order: 移动下单系统
- OnlineMall: 微信商城系统

## 产品迭代

### 第一代产品（划分标准是后台样式结构）

目前这部分的都集中在Prototype_fei.sketch的文件内，未来这几个系统会慢慢地单独迁移出来，独立成一个Sketch文件

- 在线试戴系统：这个为第一代试戴系统，无用户ID
- 移动下单系统
- 红包兑换系统
- 微信商城系统

<!-- more -->

### 第二代产品

- 营销互动系统（TryOnSys_fei.sketch）
- 微信公号产品模块（WxSys_fei.sketch）
	- 新品发布功能
	- 会员数据功能
	- 主动营销功能
- 移动下单系统（OrderSys_fei.sketch）
	
# 文件内Page命名规则

![page-name](http://oo0lr6twe.bkt.clouddn.com/sketch-name-sketch-page.png)

- UX/App/模块名称：设计移动端页面
- UX/Web/模块名称：设计电脑端页面
- Map/App/模块名称：描述移动端页面关系 ，备注页面信息
- Map/Web/模块名称：描述电脑端页面关系，备注页面信息


# Page内Artboard命名规则

![artboard](http://oo0lr6twe.bkt.clouddn.com/sketch-name-sketch-artboard.png)

产品面包屑（如：首页\产品列表\产品详情），中间用\（反斜杠）隔开（反斜杠的好处是导出的时候不会跟macOS的文件命名规则冲突）


# Symbols命名规则

Symbols是控件的模板，合理的命名可以有效减少寻找时间，对其的命名需要对UI控件有初步的了解，详情可以了解一些现有的产品设计规范

- [苹果设计规范](https://developer.apple.com/ios/human-interface-guidelines/ui-controls/buttons/)
- [AntDesign设计规范](https://ant.design/docs/react/introduce)

目前可分的大类可以是：

- View : 一些展示性的元素
	- Text 文字类的
	- Image 图片类的
	- Card  图文卡牌的展示
	- Table 表格的展示
	- ….
- Control：一些控制类的元素
	- Btn 按钮
	- Picker 选择器
	- Stepper 加减步进器
	- Select 下拉菜单
- Navi(Navigation) : 导航栏类的元素，一般是各种bar
	- Menu 菜单栏
	- Tab 

