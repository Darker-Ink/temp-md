# ComboBoxComponent

**Package:** `org.rusherhack.client.api.ui.window.content.component`

**Source:** `org/rusherhack/client/api/ui/window/content/component/ComboBoxComponent.java`

## Overview

`ComboBoxComponent` is a class that extends [WindowContent](WindowContent.md).

## Constructor

```java
public ComboBoxComponent(Window window, String[] options)
```

```java
public ComboBoxComponent(Window window, Enum<?> enumConstant)
```

```java
public ComboBoxComponent(Window window, String[] options, int selected, Consumer<String> callback)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| options | `String` | private , final |
| selected | `int` | private |
| height | `double` | private |
| isOpen | `boolean` | private |
| callback | `Consumer`<`String`> | private |


## Methods

### renderContent()

```java
public void renderContent(double mouseX, double mouseY, WindowView parent)
```

### unfocus()

```java
public void unfocus()
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

### setHeight()

```java
public void setHeight(double height)
```

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

### getOptions()

```java
public String[] getOptions()
```

**Returns:** `String`[]

### getSelectedOption()

```java
public String getSelectedOption()
```

**Returns:** `String`

### getSelected()

```java
public int getSelected()
```

**Returns:** `int`

### setSelected()

```java
public void setSelected(int selected)
```

### isOpen()

```java
public boolean isOpen()
```

**Returns:** `boolean`

### setOpen()

```java
public void setOpen(boolean open)
```

### getCallback()

```java
public Consumer<String> getCallback()
```

**Returns:** `Consumer`<`String`>

### setCallback()

```java
public void setCallback(Consumer<String> callback)
```

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
