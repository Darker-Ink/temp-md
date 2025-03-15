# WindowView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/WindowView.java`

A WindowView is a WindowContent that is able to render a set of other WindowContents in a defined way.



WindowViews should also be sure to set the position of the WindowContent before rendering it so that it is aware of its position.
* **Author:** John200410



## Overview

`WindowView` is a class that extends [WindowContent](WindowContent.md) and implements [INamed](INamed.md).

## Constructor

```java
public WindowView(Window window, List<? extends WindowContent> contentList)
```

```java
public WindowView(String name, Window window, List<? extends WindowContent> contentList)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| viewWidth | `double` | private |
| viewHeight | `double` | private |
| contentList | `List`<`? extends WindowContent`> | protected |
| viewName | `String` | private |


## Methods

### renderViewContent()

```java
public , abstract void renderViewContent(double mouseX, double mouseY)
```

### renderContent()

```java
public void renderContent(double mouseX, double mouseY, WindowView parent)
```

### unfocus()

```java
public void unfocus()
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

### charTyped()

```java
public boolean charTyped(char character)
```

**Returns:** `boolean`

### keyTyped()

```java
public boolean keyTyped(int key, int scanCode, int modifiers)
```

**Returns:** `boolean`

### mouseScrolled()

```java
public boolean mouseScrolled(double mouseX, double mouseY, double delta)
```

**Returns:** `boolean`

### tick()

```java
public void tick()
```

### setViewWidth()

```java
public void setViewWidth(double viewWidth)
```

### setViewHeight()

```java
public void setViewHeight(double viewHeight)
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

### getViewWidth()

```java
public double getViewWidth()
```

**Returns:** `double`

### getViewHeight()

```java
public double getViewHeight()
```

**Returns:** `double`

### getName()

```java
public String getName()
```

**Returns:** `String`

### getContent()

```java
public List<WindowContent> getContent()
```

**Returns:** `List`<[WindowContent](WindowContent.md)>

### setContentList()

```java
public void setContentList(List<? extends WindowContent> contentList)
```

### getHandler()

```java
protected WindowHandlerBase getHandler()
```

**Returns:** [WindowHandlerBase](WindowHandlerBase.md)

### getViewHandler()

```java
protected WindowViewHandlerBase getViewHandler()
```

**Returns:** [WindowViewHandlerBase](WindowViewHandlerBase.md)

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
