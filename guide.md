## 1，数据指标搭建
> 企业数字化转型让数据价值化：

![Alt text](image-1.png)
> 指标管理混乱，数据价值未充分发挥：

![Alt text](image-3.png)
> 指标管理目标：

![Alt text](image-4.png)
  ### 1.1，如何构建指标体系
![Alt text](image-5.png)
  > 搭建目标：

![Alt text](image.png)
  > 需求分析：

![Alt text](image-6.png)
  > 指标设计-基础：

![Alt text](image-7.png)
  > 指标设计组成：

![Alt text](image-8.png)
  > 指标设计分类：

![Alt text](image-9.png)
  > 指标设计落地：

![Alt text](image-10.png)
  > 指标设计开发：

![Alt text](image-11.png)
  > 产品架构图：

![Alt text](image-13.png)
### 1.2，案例xx银行指标体系
![Alt text](image-12.png)
  > 项目建设过程：

![Alt text](image-14.png)
  > 部分功能演示：

![Alt text](image-15.png)
![Alt text](image-16.png)

## 2，第三方支付接入基本原理和流程
> 第三方支付：

  指具备一定实力和信誉保障的独立机构，通过与银联或网联对接，从而促成交易双方进行交易的网络支付模式，例如微信支付、支付宝、京东支付、云闪付等。
> 可实现的能力：

  通过第三方支付接口实现网站、公众号、小程序、APP等场景在线收款
  支付后通过异步回调控制后续业务
  提供订单查询、账单、对账等相关技术服务
  使用微信分账等资金服务
> 微信账户介绍：

![Alt text](image-18.png)
> 支付宝账户介绍：

![Alt text](image-17.png)
> 整体业务流程：

![Alt text](image-19.png)
> API交互流程：

![Alt text](image-20.png)
![Alt text](image-22.png)
> 名词概念：

异步通知：指用户支付成功后，程序通过服务端之间的通讯达到接受支付结果的目的，交互过程用户无感知；

同步通知：指用户支付成功后，用户终端（pc、小程序、APP等）页面所发生的的跳转行为，交互过程用户可以感知到；

