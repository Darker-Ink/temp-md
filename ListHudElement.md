# ListHudElement

**Package:** `org.rusherhack.client.api.feature.hud`

**Source:** `org/rusherhack/client/api/feature/hud/ListHudElement.java`

A hud element that will display a list of items
* **Author:** John200410 6/9/2023



## Overview

`ListHudElement` is a class that extends [HudElement](HudElement.md).

## Constructor

```java
public ListHudElement(String name)
```

```java
public ListHudElement(String name, boolean sorting)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| width | `double` | private |
| height | `double` | private |
| cache | `List`<`String`> | private |
| members | `List`<[ListItem](ListItem.md)> | private |
| sorting | `boolean` | private , final |
| max | `int` | private |
| color | [ColorSetting](ColorSetting.md) | protected , final |
| colorMode | [EnumSetting](EnumSetting.md)<[ColorMode](ColorMode.md)> | protected , final |
| sortMode | [EnumSetting](EnumSetting.md)<[SortingMode](SortingMode.md)> | protected , final |
| animations | [BooleanSetting](BooleanSetting.md) | protected , final |


## Methods

### renderContent()

```java
public void renderContent(RenderContext context, double mouseX, double mouseY)
```

### renderList()

```java
private void renderList(RenderContext renderContext)
```

### tick()

```java
public void tick()
```

### resort()

```java
public void resort()
```

### setMax()

```java
public void setMax(int max)
```

### add()

```java
public void add(ListItem member)
```

### getWidth()

```java
public double getWidth()
```

**Returns:** `double`

### getHeight()

```java
public double getHeight()
```

**Returns:** `double`

### getMembers()

```java
public List<ListItem> getMembers()
```

**Returns:** `List`<[ListItem](ListItem.md)>

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
