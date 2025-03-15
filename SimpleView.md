# SimpleView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/SimpleView.java`

## Overview

`SimpleView` is a class that extends [WindowView](WindowView.md).

## Constructor

```java
public SimpleView(Window window, List<? extends WindowContent> contentList)
```

```java
public SimpleView(String name, Window window, List<? extends WindowContent> contentList)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| alignment | [Alignment](Alignment.md) | protected |
| topPadding | `double` | protected |
| leftPadding | `double` | protected |
| contentPadding | `double` | protected |
| viewWidthModifier | `double` | private |


## Methods

### renderViewContent()

```java
public void renderViewContent(double mouseX, double mouseY)
```

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

### getTopOffset()

```java
protected double getTopOffset()
```

**Returns:** `double`

### getLeftOffset()

```java
protected double getLeftOffset()
```

**Returns:** `double`

### setTopPadding()

```java
public void setTopPadding(double topPadding)
```

### setLeftPadding()

```java
public void setLeftPadding(double leftPadding)
```

### setContentPadding()

```java
public void setContentPadding(double contentPadding)
```

### setViewWidthModifier()

```java
public void setViewWidthModifier(double viewWidthModifier)
```

### setAlignment()

```java
public void setAlignment(Alignment alignment)
```

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
