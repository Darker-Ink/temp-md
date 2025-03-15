# TextComponent

**Package:** `org.rusherhack.client.api.ui.window.content.component`

**Source:** `org/rusherhack/client/api/ui/window/content/component/TextComponent.java`

A simple text content
* **Author:** John200410



## Overview

`TextComponent` is a class that extends [WindowContent](WindowContent.md).

## Constructor

```java
public TextComponent(Window window)
```

```java
public TextComponent(Window window, String text)
```

```java
public TextComponent(Window window, String text, boolean wrap)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| text | `String` | protected |


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

### mouseClicked()

```java
public boolean mouseClicked(double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### getText()

```java
public String getText()
```

**Returns:** `String`

### setText()

```java
public void setText(String text)
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

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
