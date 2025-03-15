# TextHudElement

**Package:** `org.rusherhack.client.api.feature.hud`

**Source:** `org/rusherhack/client/api/feature/hud/TextHudElement.java`

Basic hud element with text and a label
* **Author:** John200410 1/4/2023



## Overview

`TextHudElement` is a class that extends [HudElement](HudElement.md).

## Constructor

```java
public TextHudElement(String name)
```

```java
public TextHudElement(String name, boolean labeled)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| PADDING | `double` | public , static , final |
| labeled | `boolean` | private , final |
| widthCache | `double` | private |
| color | [ColorSetting](ColorSetting.md) | private , final |
| labelVisible | [BooleanSetting](BooleanSetting.md) | private , final |
| labelColor | [ColorSetting](ColorSetting.md) | private , final |
| colon | [BooleanSetting](BooleanSetting.md) | private , final |


## Methods

### renderContent()

```java
public void renderContent(RenderContext context, double mouseX, double mouseY)
```

### getLabel()

```java
public String getLabel()
```

**Returns**: the label of this hud element



**Returns:** `String`

### getText()

```java
public , abstract String getText()
```

**Returns**: the text to be displayed



**Returns:** `String`

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

### shouldUpdateAlignment()

```java
public boolean shouldUpdateAlignment()
```

these are too simple and dont have to be re-aligned

**Returns:** `boolean`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
