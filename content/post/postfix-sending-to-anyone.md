---
title: "Allow Postfix to Send Mail to Anyone"
date: 2019-09-28T00:20:25+08:00
draft: false
---

in /etc/postfix/main.cf, change:

```
inet_interfaces = localhost
```

to
```
inet_interfaces = all
```

And restart postfix accordingly.
