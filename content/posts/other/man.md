---
title: "man 手册查看约定（IOS 命令参考约定）"
date: 2026-05-27T00:00:00+08:00
draft: false
summary: "Linux man 手册参数格式说明，以及 IOS 命令参考约定解析。"
---

# man 手册查看约定

如下所示：

```bash
man ip
```

截取的一部分：

---

## NAME

```text
ip - show / manipulate routing, devices, policy routing and tunnels
```

---

## SYNOPSIS

```text
ip [ OPTIONS ] OBJECT { COMMAND | help }
```

---

# IOS 命令参考约定

## 1、互斥元素

```text
|
```

表示互斥。

---

## 2、中括号

```text
[]
```

表示可选项。

---

## 3、大括号

```text
{}
```

表示必选项。

---

## 4、中括号内的大括号

```text
[{}]
```

表示可选项中的必选项。
