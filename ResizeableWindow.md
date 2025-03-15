# ResizeableWindow

**Package:** `org.rusherhack.client.api.feature.window`

**Source:** `org/rusherhack/client/api/feature/window/ResizeableWindow.java`

A resizeable window
* **Author:** John200410



## Overview

`ResizeableWindow` is a class that extends [PinnableWindow](PinnableWindow.md).

## Constructor

```java
public ResizeableWindow(String title, double width, double height)
```

```java
public ResizeableWindow(String title, double x, double y, double width, double height)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| minWidth | `double` | private |
| minHeight | `double` | private |
| maxWidth | `double` | private |
| maxHeight | `double` | private |
| resizing | `boolean` | private |
| resizeDeltaX | `double` | private |
| resizeDeltaY | `double` | private |


## Methods

### mouseClicked()

```java
public boolean mouseClicked(double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### mouseReleased()

```java
public void mouseReleased(double mouseX, double mouseY, int button)
```

### mouseMoved()

```java
public void mouseMoved(double mouseX, double mouseY)
```

### setResizing()

```java
public void setResizing(boolean resizing, double resizeDeltaX, double resizeDeltaY)
```

### setMaxWidth()

```java
public void setMaxWidth(double maxWidth)
```

### setMaxHeight()

```java
public void setMaxHeight(double maxHeight)
```

### setMinWidth()

```java
public void setMinWidth(double minWidth)
```

### setMinHeight()

```java
public void setMinHeight(double minHeight)
```

### isResizing()

```java
public boolean isResizing()
```

**Returns:** `boolean`

### serialize()

```java
public JsonElement serialize()
```

**Returns:** `JsonElement`

### deserialize()

```java
public boolean deserialize(JsonElement jsonElement)
```

**Returns:** `boolean`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
