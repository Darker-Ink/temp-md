# ParagraphComponent

**Package:** `org.rusherhack.client.api.ui.window.content.component`

**Source:** `org/rusherhack/client/api/ui/window/content/component/ParagraphComponent.java`

A TextContent with line wrapping
* **Author:** John200410



## Overview

`ParagraphComponent` is a class that extends [TextComponent](TextComponent.md).

## Constructor

```java
public ParagraphComponent(Window window)
```

```java
public ParagraphComponent(Window window, String text)
```

```java
public ParagraphComponent(Window window, String text, double lineSpacing)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| lineSpacing | `double` | protected |
| parent | [WindowView](WindowView.md) | protected |
| heightCache | `double` | protected |
| color | `int` | protected |


## Methods

### renderContent()

```java
public void renderContent(double mouseX, double mouseY, WindowView parent)
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

### updateHeight()

```java
public void updateHeight()
```

### setLineSpacing()

```java
public void setLineSpacing(double lineSpacing)
```

### setColor()

```java
public void setColor(int color)
```

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
