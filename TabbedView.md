# TabbedView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/TabbedView.java`

A view with different tabs.
WindowViews in the content list are rendered in tabs, while other content is rendered at the bottom below the tab view.
* **Author:** John200410



## Overview

`TabbedView` is a class that extends [SimpleView](SimpleView.md).

## Constructor

```java
public TabbedView(Window window, List<WindowContent> contentList)
```

```java
public TabbedView(String name, Window window, List<WindowContent> contentList)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| activeTabView | [WindowView](WindowView.md) | private |


## Methods

### renderViewContent()

```java
public void renderViewContent(double mouseX, double mouseY)
```

tabview rendering should be handled in the WindowViewHandler

### getContent()

```java
public List<WindowContent> getContent()
```

**Returns**: list of persistent content that should be rendered below the tab view



**Returns:** `List`<[WindowContent](WindowContent.md)>

### setActiveTabView()

```java
public void setActiveTabView(WindowView activeTabView)
```

### getActiveTabView()

```java
public WindowView getActiveTabView()
```

**Returns:** [WindowView](WindowView.md)

### getTabs()

```java
public List<WindowView> getTabs()
```

**Returns:** `List`<[WindowView](WindowView.md)>

### getTabViewHeight()

```java
public double getTabViewHeight()
```

this isnt accurate its just used as a guide to know where persistent content should be rendered

**Returns:** `double`

### getPersistentContentHeight()

```java
public double getPersistentContentHeight()
```

**Returns:** `double`

### getTopOffset()

```java
protected double getTopOffset()
```

render the persistent content below the tab view

**Returns:** `double`

### getLeftOffset()

```java
protected double getLeftOffset()
```

**Returns:** `double`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
