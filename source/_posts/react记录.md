---
title: react记录
date: 2020-03-31 18:01:08
tags:
---
# 路动态路由改变组件内容不更新的情况(实际是生命函数的使用)
![a a](/img/react01.png)
* 此处是this.props.match.params的动态路由值改变时调用componentDidUpdate
* 注意componentDidUpdate的自带参数非常好用
![a a](/img/react02.png)
