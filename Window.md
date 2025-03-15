# Window

**Package:** `org.rusherhack.client.api.feature.window`

**Source:** `org/rusherhack/client/api/feature/window/Window.java`

**Author:** John200410



## Overview

`Window` is a class that extends [ElementBase](ElementBase.md) and implements [IFeatureConfigurable](IFeatureConfigurable.md), [Globals](Globals.md), [IDraggable](IDraggable.md), [IScrollable](IScrollable.md), [ITypeable](ITypeable.md), [ITickable](ITickable.md), [IHideable](IHideable.md), [IBindable](IBindable.md), [JsonSerializable](JsonSerializable.md).

## Constructor

```java
public Window(String title, double width, double height)
```

Constructs a new Window with the specified title and size. The position of the window is set to (100, 100).
* **Parameter `title`**: the title of the window


**Parameter `width`**: the width of the window


**Parameter `height`**: the height of the window



```java
public Window(String title, double x, double y, double width, double height)
```

Constructs a new Window with the specified title, position and size.
* **Parameter `title`**: the title of the window


**Parameter `x`**: the x-coordinate of the window's position


**Parameter `y`**: the y-coordinate of the window's position


**Parameter `width`**: the width of the window


**Parameter `height`**: the height of the window



## Fields

| Name | Type | Modifiers |
|------|------|----------|
| title | `String` | private |
| description | `String` | private |
| icon | [IGraphic](IGraphic.md) | private |
| settings | `List`<[Setting](Setting.md)<`?`>> | private , final |
| width | `double` | protected |
| height | `double` | protected |
| focused | `boolean` | private |
| hidden | `boolean` | private |
| dragging | `boolean` | private |
| dragDeltaX | `double` | private |
| dragDeltaY | `double` | private |
| defaultX | `double` | private , final |
| defaultY | `double` | private , final |
| defaultWidth | `double` | private , final |
| defaultHeight | `double` | private , final |


## Methods

### getRootView()

```java
public , abstract WindowView getRootView()
```

The root view that should contain all of this window's content
* **Returns**: the root view of this window



**Returns:** [WindowView](WindowView.md)

### mouseClicked()

```java
public boolean mouseClicked(double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### mouseReleased()

```java
public void mouseReleased(double mouseX, double mouseY, int button)
```

### mouseMoved()

```java
public void mouseMoved(double mouseX, double mouseY)
```

### mouseScrolled()

```java
public boolean mouseScrolled(double mouseX, double mouseY, double delta)
```

**Returns:** `boolean`

### tick()

```java
public void tick()
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

### isHovered()

```java
public boolean isHovered(double mouseX, double mouseY)
```

**Returns:** `boolean`

### getName()

```java
public String getName()
```

**Returns:** `String`

### getDescription()

```java
public String getDescription()
```

**Returns:** `String`

### setDescription()

```java
public void setDescription(String description)
```

### getSettings()

```java
public List<Setting<?>> getSettings()
```

**Returns:** `List`<[Setting](Setting.md)<`?`>>

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

### isHidden()

```java
public boolean isHidden()
```

**Returns:** `boolean`

### setHidden()

```java
public void setHidden(boolean hidden)
```

### reset()

```java
public boolean reset()
```

Resets this window's position and visibility
* **Returns**: true if the feature was reset



**Returns:** `boolean`

### getBindReference()

```java
public String getBindReference()
```

String representation of this bindable object

**Returns:** `String`

### onKeybindEvent()

```java
public void onKeybindEvent()
```

### onClose()

```java
public void onClose()
```

### isDragging()

```java
public boolean isDragging()
```

**Returns:** `boolean`

### setDragging()

```java
public void setDragging(boolean dragging, double deltaX, double deltaY)
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

### setIcon()

```java
public void setIcon(IGraphic icon)
```

### getIcon()

```java
public IGraphic getIcon()
```

**Returns:** [IGraphic](IGraphic.md)

### renderIcon()

```java
public boolean renderIcon(double x, double y, double width, double height)
```

Renders the icon of this window
* **Returns**: true if the icon was rendered, false otherwise



**Returns:** `boolean`

### serialize()

```java
public JsonElement serialize()
```

**Returns:** `JsonElement`

### deserialize()

```java
public boolean deserialize(JsonElement obj)
```

**Returns:** `boolean`

### getRenderer()

```java
public IRenderer2D getRenderer()
```

**Returns:** [IRenderer2D](IRenderer2D.md)

### getFontRenderer()

```java
public IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](IFontRenderer.md)

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
