title: 如何区分 `<appId>.wilddogio.com` 和` <appId>.wilddog.com` 的使用方式？
tag:实时数据同步
---

- 在野狗初始化时的 `syncURL`中，使用`<appId>.wilddogio.com`;
- 在野狗初始化时的 `authDomain`中，使用`<appId>.wilddog.com`；

两者不能颠倒使用，否则程序初始化会失败。

