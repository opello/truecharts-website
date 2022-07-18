# 输入验证

## 管理员用户名

Spotweb 管理员的用户名有一些限制。

* 不允许使用以下单词：
  * 上角
  * mod
  * 斑点
  * 管理员
  * 德拉兹克文
  * 超级用户
  * 监督员
  * 根目录
  * 匿名的
* 以下字符是不允许的：
  * <
  * \>
* 正则表达式用于验证用户名 (您可以尝试在这里运行 [](https://regex101.com/r/LA4Io7/1))： `^((?!god|mod|spot|admin|drazix|superuser|Superor|root|anonymous)[^<>])*$`

## 管理员名字

Spotweb 中的名字和姓有一些限制。

* 以下字符是不允许的：
  * <
  * \>
* 两个字符的最小长度是强制执行
* 正则表达式用于验证名字和姓氏(你可以尝试在这里 [生活](https://regex101.com/r/x2KGnU/1)): `^([^<>]{2})[^<>]*)$`

## 管理员电子邮件

电子邮件添加是使用内置的 `_FILTER_VALIDATE_EMAIL` 在Spotweb 中验证的。

* 正则表达式用于验证电子邮件 (您可以尝试在这里运行 [](https://regex101.com/r/yEmCoL/1)): ``^[a-zA-Z0-9。 #$%&'*+\/=?^_`{|}~-]+@[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])?(?:\.[a-zA-Z0-9](?:[a-zA-Z0-9-]{0,61}[a-zA-Z0-9])*$``

---
如果您找到了一个您认为需要验证的字段，请在 github 上打开一个问题