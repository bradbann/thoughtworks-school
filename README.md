# ThoughtWorks-XUPT2016-Programming

## ThoughtWorks 西安邮电大学暑期特训营（2016）训练集

[ThoughtWorks 西安邮电大学暑期特训营（2016）报名点](https://jinshuju.net/f/rHT9Fo)

暑期培训时间为2016年 7.18~8.26 每周6天，每天7+小时

培训期间，每日尽可能更新当日进度至本仓库

## 项目训练

* [take-out-food](https://github.com/freewind/take-out-food)

* [dojo](https://github.com/hkliya/dojo)

* [big-class-test-2](https://github.com/twa-camp-2016/big-class-test-2)

* [postnet](https://github.com/linwenjun/postnet)

* [postnet-base-for-big-class-room](https://github.com/twa-camp-2016/postnet-base-for-big-classroom)

* [collection-calculate-camp](https://github.com/iamcoach/collection-calculate-camp)

* [recruiting-system](https://github.com/thoughtworks-academy/recruiting-system)

## 第一周

## 第二周

## 第三周

thoughtworksXUPT2016

    整理自身（分周）
    node 安装 npm install init

    装 nvm npm nrm node （nrm ls      nrm use *）
    npm install nrm -g

    npm install jasmine -D
    ./node_modules/.bin/jasmine (init)
    vim package.json   test:”jasmine”
    npm test
    websterm -> tools -> creatcommand -> storm

    const * = require(“”);
    module.exports = 函数名(对象);
    
    谷歌插件
        postman
        octotree
        远方 New Tab
        
    express 版的 postnet
        5种发送参数的方式   —   5个小demo
    
    express superangent supertest
    
    
    git  逐步提交 版本回退 单个文件分开提交
    
    格式化代码
    
    结对编程
    
    trello

    函数读取变量的位置
        全局变量
        参数
        文件流

xmind

## 基于 pipeline 的 tasking 方法

### pipeline 画图规范要点

* 用动词和小驼峰法命名函数

* 输入数据不能写到输出线上

* 每个对象要说明数据类型

* 每个函数只处理一个功能 -- 便于分块和命名

* 图中只需出现英文

### 常见动词

|动词|解释|
|--|--|
|get|获取|
|generate|创建 生成|
|find|获取集合中的子集|
|calculate|计算|
|merge|merge|
|split|拆分| 
|is|是...|
|has|拥有|

### 零散笔记

拿到一个开发需求 --> 画 pipeline 图 --> 写 tasking 测试函数 --> 写核心函数 --> 进行测试

每个函数的圈复杂度要有所控制（每有一个if/for/while等圈复杂度加一），圈复杂度越小越利于维护

人肉测试 -- console.log()

单元测试 -- jasmine

JS语法测试 -- JSlint

工程实践

TDD 与 BDD

极限编程

系统集成

一个优化漂亮的代码可以成为自注释

一个漂亮/优化符合命名/使用规范的代码可以成为自注释（不需要写注释）

代码是给人看的，偶尔在机器上跑一下

Atwood定律：Any application that can be written in JavaScript,will eventually be written in JavaScript

马丁·福勒：计算机科学最难应付的两件事——命名和缓存失效。


持续交付（重构）

* 旧的不变

* 新的创建

* 单步切换

* 旧的再见


面向对象

* 三大基石/五大原则

* 对象/类/实例

* 封装/继承

* 单一职责

怎样的测试算是好的测试

5W1H分析法 -- 六何分析法

* 1932年，美国政治学家拉斯维尔提出“5W分析法”，后经过人们的不断运用和总结，逐步形成了一套成熟的“5W+IH”模式。

* what
* where
* when
* who
* why

* how

HTTP

  协议
  端口