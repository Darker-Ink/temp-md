# Column

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/ListView.java`

A column in a list view

## Overview

`Column` is a class and implements [INamed](INamed.md).

## Constructor

```java
public Column(String name)
```

```java
public Column(String name, double widthWeight)
```

```java
public Column(String name, Comparator<T> comparator, double widthWeight)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | `String` | private , final |
| comparator | `Comparator`<`T`> | private |
| widthWeight | `double` | private , final |


## Methods

### getName()

```java
public String getName()
```

**Returns:** `String`

### getComparator()

```java
public Comparator<T> getComparator()
```

**Returns:** `Comparator`<`T`>

### setComparator()

```java
public void setComparator(Comparator<T> comparator)
```

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
