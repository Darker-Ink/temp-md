# CheckBoxComponent

**Package:** `org.rusherhack.client.api.ui.window.content.component`

**Source:** `org/rusherhack/client/api/ui/window/content/component/CheckBoxComponent.java`

## Overview

`CheckBoxComponent` is a class that extends [WindowContent](WindowContent.md).

## Constructor

```java
public CheckBoxComponent(Window window, String label, boolean value)
```

```java
public CheckBoxComponent(Window window, double size, String label, boolean value)
```

```java
public CheckBoxComponent(Window window, double size, String label, boolean value, Consumer<Boolean> callback)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| size | `double` | private , final |
| label | `String` | private |
| value | `boolean` | private |
| valueConsumer | `Consumer`<`Boolean`> | private |


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

### getLabel()

```java
public String getLabel()
```

**Returns:** `String`

### setLabel()

```java
public void setLabel(String label)
```

### getValue()

```java
public boolean getValue()
```

**Returns:** `boolean`

### setValue()

```java
public void setValue(boolean value)
```

### setValueConsumer()

```java
public void setValueConsumer(Consumer<Boolean> valueConsumer)
```

### getSize()

```java
public double getSize()
```

**Returns:** `double`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
