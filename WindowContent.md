# WindowContent

**Package:** `org.rusherhack.client.api.ui.window.content`

**Source:** `org/rusherhack/client/api/ui/window/content/WindowContent.java`

Content that can be rendered inside of a Window
* **Author:** John200410



## Overview

`WindowContent` is a class and implements [IClickable](IClickable.md), [ITypeable](ITypeable.md), [IScrollable](IScrollable.md), [ITickable](ITickable.md).

## Constructor

```java
public WindowContent(Window window)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| window | [Window](Window.md) | private , final |
| x | `double` | protected |
| y | `double` | protected |
| contextMenu | `List`<[ContextAction](ContextAction.md)> | protected |


## Methods

### renderContent()

```java
public , abstract void renderContent(double mouseX, double mouseY, WindowView parent)
```

### getWidth()

```java
public , abstract double getWidth()
```

**Returns:** `double`

### getHeight()

```java
public , abstract double getHeight()
```

**Returns:** `double`

### getContextMenu()

```java
public List<ContextAction> getContextMenu()
```

**Returns:** `List`<[ContextAction](ContextAction.md)>

### setContextMenu()

```java
public void setContextMenu(List<ContextAction> contextMenu)
```

### unfocus()

```java
public void unfocus()
```

Called when the window loses focus. Should be used to unfocus things like text fields

### getWindow()

```java
public Window getWindow()
```

**Returns:** [Window](Window.md)

### isHovered()

```java
public boolean isHovered(double mouseX, double mouseY)
```

**Returns:** `boolean`

### setX()

```java
public double setX(double x)
```

**Returns:** `double`

### setY()

```java
public double setY(double y)
```

**Returns:** `double`

### getX()

```java
public double getX()
```

**Returns:** `double`

### getY()

```java
public double getY()
```

**Returns:** `double`

### getRenderer()

```java
public IRenderer2D getRenderer()
```

**Returns:** [IRenderer2D](IRenderer2D.md)

### getFontRenderer()

```java
public IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](IFontRenderer.md)

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
