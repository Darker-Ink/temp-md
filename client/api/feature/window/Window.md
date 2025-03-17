# Window

**Package:** `org.rusherhack.client.api.feature.window`

**Source:** `org/rusherhack/client/api/feature/window/Window.java`

**Author:** John200410



## Overview

`Window` is a class that extends [ElementBase](/client/api/ui/ElementBase.md) and implements [IFeatureConfigurable](/core/feature/IFeatureConfigurable.md), [Globals](/client/api/Globals.md), [IDraggable](/core/interfaces/IDraggable.md), [IScrollable](/core/interfaces/IScrollable.md), [ITypeable](/core/interfaces/ITypeable.md), [ITickable](/core/interfaces/ITickable.md), [IHideable](/core/interfaces/IHideable.md), [IBindable](/core/bind/IBindable.md), [JsonSerializable](/core/serialize/JsonSerializable.md).

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
| title | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private |
| description | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private |
| icon | [IGraphic](/client/api/render/graphic/IGraphic.md) | private |
| settings | `List`<[Setting](/core/setting/Setting.md)<`?`>> | private final |
| width | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | protected |
| height | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | protected |
| focused | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |
| hidden | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |
| dragging | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |
| dragDeltaX | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private |
| dragDeltaY | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private |
| defaultX | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private final |
| defaultY | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private final |
| defaultWidth | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private final |
| defaultHeight | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private final |


## Methods

### getRootView()

```java
public abstract WindowView getRootView()
```

The root view that should contain all of this window's content
* **Returns**: the root view of this window



**Returns:** [WindowView](/client/api/ui/window/view/WindowView.md)

### mouseClicked()

```java
public boolean mouseClicked(double mouseX, double mouseY, int button)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

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

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### tick()

```java
public void tick()
```

### charTyped()

```java
public boolean charTyped(char character)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### keyTyped()

```java
public boolean keyTyped(int key, int scanCode, int modifiers)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### isHovered()

```java
public boolean isHovered(double mouseX, double mouseY)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### getName()

```java
public String getName()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getDescription()

```java
public String getDescription()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### setDescription()

```java
public void setDescription(String description)
```

### getSettings()

```java
public List<Setting<?>> getSettings()
```

**Returns:** `List`<[Setting](/core/setting/Setting.md)<`?`>>

### getWidth()

```java
public double getWidth()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getHeight()

```java
public double getHeight()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### isHidden()

```java
public boolean isHidden()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

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



**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### getBindReference()

```java
public String getBindReference()
```

String representation of this bindable object

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

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

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### setDragging()

```java
public void setDragging(boolean dragging, double deltaX, double deltaY)
```

### isFocused()

```java
public boolean isFocused()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

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

**Returns:** [IGraphic](/client/api/render/graphic/IGraphic.md)

### renderIcon()

```java
public boolean renderIcon(double x, double y, double width, double height)
```

Renders the icon of this window
* **Returns**: true if the icon was rendered, false otherwise



**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### serialize()

```java
public JsonElement serialize()
```

**Returns:** `JsonElement`

### deserialize()

```java
public boolean deserialize(JsonElement obj)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### getRenderer()

```java
public IRenderer2D getRenderer()
```

**Returns:** [IRenderer2D](/client/api/render/IRenderer2D.md)

### getFontRenderer()

```java
public IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](/client/api/render/font/IFontRenderer.md)

