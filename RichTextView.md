# RichTextView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/RichTextView.java`

A scrollable view meant for displaying logs



TODO: add selection copying
* **Author:** John200410 11/22/2023



## Overview

`RichTextView` is a class that extends [ScrollableView](ScrollableView.md).

## Constructor

```java
public RichTextView(Window window)
```

```java
public RichTextView(String name, Window window)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| textComponents | `List`<[RichTextComponent](RichTextComponent.md)> | private , final |
| queue | `Queue`<[RichTextComponent](RichTextComponent.md)> | private , final |


## Methods

### add()

```java
public void add(String text, int color)
```

### add()

```java
public void add(Component text, int color)
```

### renderViewContent()

```java
public void renderViewContent(double mouseX, double mouseY)
```

### newComponent()

```java
protected void newComponent(RichTextComponent c, int color)
```

### clear()

```java
public void clear()
```

### shouldClampToBottom()

```java
protected boolean shouldClampToBottom()
```

**Returns:** `boolean`

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
