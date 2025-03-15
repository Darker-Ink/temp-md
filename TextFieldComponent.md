# TextFieldComponent

**Package:** `org.rusherhack.client.api.ui.window.content.component`

**Source:** `org/rusherhack/client/api/ui/window/content/component/TextFieldComponent.java`

## Overview

`TextFieldComponent` is a class that extends [WindowContent](WindowContent.md).

## Constructor

```java
public TextFieldComponent(Window window, double width)
```

```java
public TextFieldComponent(Window window, String label, double width)
```

```java
public TextFieldComponent(Window window, String label, double width, boolean censored)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| textField | [TextField](TextField.md) | private , final |
| label | `String` | private |
| censored | `boolean` | private , final |
| focused | `boolean` | private |
| inputDelay | [Timer](Timer.md) | private , final |
| width | `double` | private |
| heightRatio | `double` | private , final |
| cursorBlinkTimer | [Timer](Timer.md) | private , final |
| blink | `boolean` | private |
| returnCallback | `Consumer`<`String`> | private |
| characterFilter | `Predicate`<`Character`> | private |


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

### getDisplayValue()

```java
public String getDisplayValue()
```

**Returns:** `String`

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
public String getValue()
```

**Returns:** `String`

### setValue()

```java
public void setValue(String value)
```

### setWidth()

```java
public void setWidth(double width)
```

### setReturnCallback()

```java
public void setReturnCallback(Consumer<String> returnCallback)
```

### setCharacterFilter()

```java
public void setCharacterFilter(Predicate<Character> characterFilter)
```

### isFocused()

```java
public boolean isFocused()
```

**Returns:** `boolean`

### setFocused()

```java
public void setFocused(boolean focused)
```

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
