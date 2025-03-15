# ListItemContent

**Package:** `org.rusherhack.client.api.ui.window.content`

**Source:** `org/rusherhack/client/api/ui/window/content/ListItemContent.java`

## Overview

`ListItemContent` is a class that extends [WindowContent](WindowContent.md).

## Constructor

```java
public ListItemContent(Window window, ListView<?> listView)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| listView | [ListView](ListView.md)<`?`> | private , final |
| timeSinceLastClick | `long` | private |


## Methods

### getAsString()

```java
public , abstract String getAsString(ListView<?>.Column column)
```

**Returns:** `String`

### isSelected()

```java
public boolean isSelected()
```

**Returns:** `boolean`

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

### mouseClicked()

```java
public boolean mouseClicked(double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### mouseScrolled()

```java
public boolean mouseScrolled(double mouseX, double mouseY, double delta)
```

**Returns:** `boolean`

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

### onDoubleClick()

```java
protected void onDoubleClick()
```

### getListView()

```java
public ListView<?> getListView()
```

**Returns:** [ListView](ListView.md)<`?`>

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
