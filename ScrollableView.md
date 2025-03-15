# ScrollableView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/ScrollableView.java`

## Overview

`ScrollableView` is a class that extends [SimpleView](SimpleView.md).

## Constructor

```java
public ScrollableView(Window window, List<? extends WindowContent> contentList)
```

```java
public ScrollableView(String name, Window window, List<? extends WindowContent> contentList)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| isDraggingScrollbarGrip | `boolean` | private |
| dragDeltaY | `double` | public |
| prevMax | `double` | private |
| scrollbar | [Scrollbar](Scrollbar.md) | final |


## Methods

### renderViewContent()

```java
public void renderViewContent(double mouseX, double mouseY)
```

### shouldClampToBottom()

```java
protected boolean shouldClampToBottom()
```

**Returns:** `boolean`

### mouseScrolled()

```java
public boolean mouseScrolled(double mouseX, double mouseY, double delta)
```

**Returns:** `boolean`

### mouseReleased()

```java
public void mouseReleased(double mouseX, double mouseY, int button)
```

### getTopOffset()

```java
protected double getTopOffset()
```

**Returns:** `double`

### isScrollable()

```java
public boolean isScrollable()
```

**Returns:** `boolean`

### setDraggingGrip()

```java
public void setDraggingGrip(boolean dragging, double dragDeltaY)
```

### getScrollbar()

```java
public Scrollbar getScrollbar()
```

**Returns:** [Scrollbar](Scrollbar.md)

### getContentHeight()

```java
public double getContentHeight()
```

**Returns:** `double`

### isDraggingScrollbarGrip()

```java
public boolean isDraggingScrollbarGrip()
```

**Returns:** `boolean`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
