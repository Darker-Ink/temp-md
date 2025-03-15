# WindowHandlerBase

**Package:** `org.rusherhack.client.api.ui.window`

**Source:** `org/rusherhack/client/api/ui/window/WindowHandlerBase.java`

**Author:** John200410



## Overview

`WindowHandlerBase` is a class that extends [ElementHandlerBase](ElementHandlerBase.md).

## Constructor

```java
public WindowHandlerBase()
```

## Methods

### getViewHandler()

```java
public , abstract WindowViewHandlerBase getViewHandler()
```

Returns the view handler of this window handler.
* **Returns**: the view handler of this window handler



**Returns:** [WindowViewHandlerBase](WindowViewHandlerBase.md)

### getContentHandler()

```java
public , abstract WindowContentHandlerBase getContentHandler()
```

Returns the content handler of this window handler.
* **Returns**: the content handler of this window handler



**Returns:** [WindowContentHandlerBase](WindowContentHandlerBase.md)

### renderWindowFrame()

```java
public , abstract void renderWindowFrame(Window window, double mouseX, double mouseY)
```

Renders the frame of a window.
* **Parameter `window`**: the window


**Parameter `mouseX`**: the x-coordinate of the mouse


**Parameter `mouseY`**: the y-coordinate of the mouse



### getFramePadding()

```java
public , abstract int getFramePadding(WindowSide side)
```

Returns the frame padding of a side of a window.
* **Parameter `side`**: the side of the window


**Returns**: the frame padding of the side



**Returns:** `int`

### moveElementToTop()

```java
public void moveElementToTop(Window element)
```

### getElements()

```java
public List<Window> getElements()
```

**Returns:** `List`<[Window](Window.md)>

### renderElements()

```java
public void renderElements(RenderContext context, double mouseX, double mouseY)
```

### renderWindow()

```java
public void renderWindow(Window window, RenderContext context, double mouseX, double mouseY)
```

TODO: abstract this into ElementHandlerBase (renderElement function)

### consumeMouseClick()

```java
protected boolean consumeMouseClick(double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### consumeElementMouseClick()

```java
protected boolean consumeElementMouseClick(Window window, double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### consumeElementMouseRelease()

```java
protected boolean consumeElementMouseRelease(Window window, double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### consumeMouseMove()

```java
protected void consumeMouseMove(double mouseX, double mouseY)
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

### isElementHovered()

```java
public boolean isElementHovered(Window window, double mouseX, double mouseY)
```

Checks if a window is hovered. Can be overridden to change the hover behavior.
* **Parameter `window`**: the window


**Parameter `mouseX`**: the x-coordinate of the mouse


**Parameter `mouseY`**: the y-coordinate of the mouse


**Returns**: true if the window is hovered



**Returns:** `boolean`

### getWindowColor()

```java
public Color getWindowColor(Window window)
```

Returns the primary color of a window.
* **Parameter `window`**: the window


**Returns**: the color of the window



**Returns:** `Color`

### initialize()

```java
public void initialize()
```

unused for now

### setDefaultPositions()

```java
public void setDefaultPositions()
```

unused for now

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
