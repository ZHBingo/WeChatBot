# WeChatBot - Java

> 本项目是对 https://github.com/cixingguangming55555/wechat-bot 项目做出的JAVA版本客户端(持续跟进更新), 看了其他几个版本的 觉得写的比较乱, 该有的不该有的都在里边,看着难受, 就自己重写了下, 更简洁,方便上手

## 声明: 本项目不欢迎华为公司的拥护者(其任何产品)
> 1. 原因: 永远忘不了, [华为251](https://zh.wikipedia.org/wiki/%E8%8F%AF%E7%82%BA251%E4%BA%8B%E4%BB%B6) 对开发者的迫害, 一边打着爱国情怀卖产品, 一边迫害开发者
> 2. 你问我这样是否有用? 不,你理解错了我只是想发表自己的声音
> 3. 欢迎其他开发者,本项目MIT协议

## 快速上手

上手之前请确认您已经对微信注入了相关版本的dll

> 1. 克隆当前项目或到Releases下载代码
> 2. idea中配置打开项目, 等待maven下载相关依赖
> 3. 启动项目
> 4. 调用接口: http://localhost:8081/sendTextMsg 发送文本消息 
> 5. 当然要是熟悉文档操作也可以调用通用接口传入必要的值来进行消息的发送 通用接口地址http://localhost:8081/wechatCommon 具体使用参考接口文档介绍

## 接口文档
[点击查看接口文档](https://docs.apipost.cn/view/94356b050fc22d34)

## 更新记录

> 2021-08-02 测试:支持微信 3.3.0.115
> 
> 2021-03-31 支持微信 3.2.1.121
>
> 2021-03-28 支持微信 3.1.0.66