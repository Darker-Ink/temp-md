# PaddingContent

**Package:** `org.rusherhack.client.api.ui.window.content`

**Source:** `org/rusherhack/client/api/ui/window/content/PaddingContent.java`

**Author:** John200410 11/22/2023



## Overview

`PaddingContent` is a class that extends [WindowContent](WindowContent.md).

## Constructor

```java
public PaddingContent(Window window, double width, double height)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| width | `double` | private , final |
| height | `double` | private , final |


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

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
