# ButtonComponent

**Package:** `org.rusherhack.client.api.ui.window.content.component`

**Source:** `org/rusherhack/client/api/ui/window/content/component/ButtonComponent.java`

TODO: create interface so that ComboContent can modify width as needed
* **Author:** John200410



## Overview

`ButtonComponent` is a class that extends [WindowContent](WindowContent.md) and implements [INamed](INamed.md).

## Constructor

```java
public ButtonComponent(Window window, String label, Runnable clickAction)
```

```java
public ButtonComponent(Window window, String label, double width, double height, Runnable clickAction)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| label | `String` | private |
| width | `double` | private |
| height | `double` | private |
| enabledPredicate | `Predicate`<[ButtonComponent](ButtonComponent.md)> | private |
| pressed | `boolean` | private |
| clickAction | `Runnable` | private |


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

### setWidth()

```java
public void setWidth(double width)
```

### setHeight()

```java
public void setHeight(double height)
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

### getName()

```java
public String getName()
```

**Returns:** `String`

### setLabel()

```java
public void setLabel(String name)
```

### setAction()

```java
public void setAction(Runnable action)
```

### onClick()

```java
public void onClick()
```

### isPressed()

```java
public boolean isPressed()
```

**Returns:** `boolean`

### setPressed()

```java
public void setPressed(boolean pressed)
```

### setPredicate()

```java
public void setPredicate(Predicate<ButtonComponent> enabledPredicate)
```

### isEnabled()

```java
public boolean isEnabled()
```

**Returns:** `boolean`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
