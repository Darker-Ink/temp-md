# ComboContent

**Package:** `org.rusherhack.client.api.ui.window.content`

**Source:** `org/rusherhack/client/api/ui/window/content/ComboContent.java`

Content that bundles two or more other contents.



Useful for situations like when you need a text field and a button to be next to each other.



(this probably needs to be rewritten)
* **Author:** John200410



## Overview

`ComboContent` is a class that extends [WindowContent](WindowContent.md).

## Constructor

```java
public ComboContent(Window window)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| contents | `List`<`Pair<WindowContent`, `AnchorSide>`> | private , final |
| parent | [WindowView](WindowView.md) | private |


## Methods

### addContent()

```java
public void addContent(WindowContent content)
```

### addContent()

```java
public void addContent(WindowContent content, AnchorSide anchor)
```

### renderContent()

```java
public void renderContent(double mouseX, double mouseY, WindowView parent)
```

this can definitely be done better but my adhd meds wore off and this works good enough

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

### unfocus()

```java
public void unfocus()
```

### mouseReleased()

```java
public void mouseReleased(double mouseX, double mouseY, int button)
```

### getContents()

```java
public List<Pair<WindowContent, AnchorSide>> getContents()
```

**Returns:** `List`<`Pair<WindowContent`, `AnchorSide>`>

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
