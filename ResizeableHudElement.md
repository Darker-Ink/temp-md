# ResizeableHudElement

**Package:** `org.rusherhack.client.api.feature.hud`

**Source:** `org/rusherhack/client/api/feature/hud/ResizeableHudElement.java`

Hud element which can be scaled.
TODO: make dragging show dragging mouse cursor
* **Author:** John200410 5/29/2023



## Overview

`ResizeableHudElement` is a class that extends [HudElement](HudElement.md).

## Constructor

```java
public ResizeableHudElement(String name)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| resizing | `boolean` | private |
| resizeStartScale | `double` | private |
| resizeDeltaX | `double` | private |
| resizeDeltaY | `double` | private |
| scale | [NumberSetting](NumberSetting.md)<`Double`> | private , final |


## Methods

### mouseMoved()

```java
public void mouseMoved(double mouseX, double mouseY)
```

### mouseClicked()

```java
public boolean mouseClicked(double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### mouseReleased()

```java
public void mouseReleased(double mouseX, double mouseY, int button)
```

### getScale()

```java
public double getScale()
```

**Returns:** `double`

### render()

```java
public void render(RenderContext context, double mouseX, double mouseY)
```

### shouldUpdateAlignment()

```java
public boolean shouldUpdateAlignment()
```

**Returns:** `boolean`

### isHoveredOverIndicator()

```java
public boolean isHoveredOverIndicator(double mouseX, double mouseY)
```

**Returns:** `boolean`

### isResizing()

```java
public boolean isResizing()
```

**Returns:** `boolean`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
