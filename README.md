﻿# 电子商务项目
## 电商项目简介
电子商务项目[taoshop](https://github.com/u014427391/taoshop)</br>
本开源电商项目，SpringBoot+Dubbo技术栈实现微服务，实现一款分布式集群的电商系统。(开发中...)

## 开源协议
taoshop使用Apache2.0开源协议

## 功能
### [前台]
- [ ] 商品搜索(Solr)
- [ ] 支付功能(支付接口)
- [ ] 商品展示
- [ ] 购物车功能
- [ ] 会员中心
- [ ] 优惠券秒杀(高并发处理)
- [ ] 订单提交
- [ ] 单点登录(SSO)
- [ ] portal门户

### [后台]
- [ ] 报表统计
- [ ] SCM供应链系统
- [ ] 商品管理
- [ ] 活动管理
- [ ] 商品推荐
- [ ] 订单管理
- [ ] CMS内容管理系统
- [ ] CRM客户关系管理系统

### 技术栈
* 模板引擎：Thymeleaf
* 搜索引擎：Lucene
* 负载均衡：Nginx
* 后台主要框架：SpringBoot、Mybatis
* 微服务搭建：SpringCloud或者阿里的Dubbo
### 平台工程目录

```
├─taoshop----------------------------父项目，公共依赖
│  │
│  ├─taoshop-search--------------------------全局搜索
│  │
│  ├─taoshop-quartz-----------------------任务调度系统
│  │
│  ├─taoshop-sso-------------------------单点登录工程
│  │
│  ├─taoshop-portal--------------------------门户网站
│  │
│  ├─taoshop-cms--------------------------平台cms系统
|  |
|  |─taoshop-order--------------------------平台订单系统
│  │
│  ├─paascloud-provider
│  │  │
│  │  │
│  │  ├─taoshop-provider-osc------------------订单信息服务中心
│  │  │
│  │  └─taoshop-provider-usc------------------用户信息服务中心
│  │
│  ├─taoshop-provider-api
│  │  │
│  │  │-taoshop-provider-api-usc------------------用户信息服务API
|  |  |
│  │  └─taoshop-provider-api-osc------------------订单信息服务API
│  │
│  ├─taoshop-common
│  │  │
│  │  ├─taoshop-common-core------------------平台核心依赖服务
│  │  │
│  │  ├─taoshop-common-zk------------------zookeeper配置工程
│  │  │
│  │  ├─taoshop-common-quartz------------------任务调度服务
│  │  │
│  │  ├─taoshop-security-core------------------安全服务核心服务
│  │  │
│  │  └─taoshop-security-auth2------------------API认证授权服务
│  │




```



### 架构设计

![Image text](https://github.com/u014427391/taoshop/raw/master/screenshot/架构图20180409.png)




