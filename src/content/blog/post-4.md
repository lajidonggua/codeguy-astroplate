---
title: "Java 基础（四）：面向对象入门"
meta_title: "Java 基础（四）"
description: "类与对象、构造方法、封装的基本概念"
date: 2026-01-26T08:00:00Z
categories: ["Java 基础"]
author: "codeguy"
tags: ["java", "基础"]
draft: false
---

面向对象是 Java 的核心思想，下面是入门级别的概念梳理。

## 1. 类与对象

```java
class Person {
 String name;
 int age;
}

Person p = new Person();
p.name = "codeguy";
p.age = 18;
```

## 2. 构造方法

```java
class Person {
 String name;
 Person(String name) {
  this.name = name;
 }
}
```

## 3. 封装

- 使用 `private` 隐藏内部字段
- 通过 `get/set` 暴露必要能力
