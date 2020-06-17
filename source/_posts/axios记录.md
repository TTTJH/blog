---
title: axios记录
date: 2020-04-06 10:35:12
tags:
---
# 为axios请求头部携带token
![a a](/img/axios01.png)
```javascript
if(Cookies.get("token")){
    axios.defaults.headers.common['X-Litemall-Token'] = Cookies.get("token")
}
```
