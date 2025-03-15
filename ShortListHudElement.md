# ShortListHudElement

**Package:** `org.rusherhack.client.api.feature.hud`

**Source:** `org/rusherhack/client/api/feature/hud/ShortListHudElement.java`

**Author:** John200410 7/25/2023



## Overview

`ShortListHudElement` is a class that extends [HudElement](HudElement.md).

## Constructor

```java
public ShortListHudElement(String name)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| COMMA_SEPARATOR_COMPONENT | `Component` | public , static , final |
| PADDING | `double` | public , static , final |
| color | [ColorSetting](ColorSetting.md) | private , final |
| axis | [EnumSetting](EnumSetting.md)<[TextAxis](TextAxis.md)> | private , final |
| list | `Component` | private |
| width | `double` | private |
| height | `double` | private |


## Methods

### getComponents()

```java
public , abstract Component[] getComponents()
```

**Returns:** `Component`[]

### renderContent()

```java
public void renderContent(RenderContext context, double mouseX, double mouseY)
```

### tick()

```java
public void tick()
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

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
