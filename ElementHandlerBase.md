# ElementHandlerBase

**Package:** `org.rusherhack.client.api.ui`

**Source:** `org/rusherhack/client/api/ui/ElementHandlerBase.java`

A handler for managing multiple elements on screen.
* **Author:** John200410 3/5/2024



## Overview

`ElementHandlerBase` is a class and implements [Globals](Globals.md), [IRenderable2D](IRenderable2D.md), [IDraggable](IDraggable.md), [IScrollable](IScrollable.md), [ITypeable](ITypeable.md), [ITickable](ITickable.md), [JsonSerializable](JsonSerializable.md).

## Constructor

```java
public ElementHandlerBase(boolean scaledWithMinecraftGui)
```

**Parameter `scaledWithMinecraftGui`**: sets whether elements should be scaled with the minecraft gui



## Fields

| Name | Type | Modifiers |
|------|------|----------|
| scaledWithMinecraftGui | `boolean` | private , final |
| positionsInitialized | `boolean` | public |


## Methods

### getElements()

```java
public , abstract List<T> getElements()
```

**Returns**: elements to be handled by this handler



**Returns:** `List`<`T`>

### getElement()

```java
public Optional<T> getElement(String name)
```

Finds an element given it's name
* **Parameter `name`**: name of the element


**Returns**: the element with the name or null if not found



**Returns:** `Optional`<`T`>

### initialize()

```java
public , abstract void initialize()
```

Initialize all of the elements

### setDefaultPositions()

```java
public , abstract void setDefaultPositions()
```

Sets the default positions of the elements

### moveElementToTop()

```java
public , abstract void moveElementToTop(T element)
```

Moves the element to the top
* **Parameter `element`**: element to move to the top



### render()

```java
public void render(RenderContext context, double mouseX, double mouseY)
```

### renderElements()

```java
public void renderElements(RenderContext renderContext, double mouseX, double mouseY)
```

### tick()

```java
public void tick()
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

### mouseMoved()

```java
public void mouseMoved(double mouseX, double mouseY)
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

### isHovered()

```java
public boolean isHovered(double mouseX, double mouseY)
```

**Returns:** `boolean`

### consumeMouseClick()

```java
protected boolean consumeMouseClick(double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### consumeElementMouseClick()

```java
protected boolean consumeElementMouseClick(T element, double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### consumeMouseRelease()

```java
protected void consumeMouseRelease(double mouseX, double mouseY, int button)
```

### consumeElementMouseRelease()

```java
protected boolean consumeElementMouseRelease(T element, double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

### consumeMouseMove()

```java
protected void consumeMouseMove(double mouseX, double mouseY)
```

### consumeElementMouseMove()

```java
protected boolean consumeElementMouseMove(T element, double mouseX, double mouseY)
```

**Returns:** `boolean`

### consumeMouseScroll()

```java
protected boolean consumeMouseScroll(double mouseX, double mouseY, double delta)
```

**Returns:** `boolean`

### consumeElementMouseScroll()

```java
protected boolean consumeElementMouseScroll(T element, double mouseX, double mouseY, double delta)
```

**Returns:** `boolean`

### consumeElementCharTyped()

```java
protected boolean consumeElementCharTyped(T element, char character)
```

**Returns:** `boolean`

### consumeElementKeyTyped()

```java
protected boolean consumeElementKeyTyped(T element, int key, int scanCode, int modifiers)
```

**Returns:** `boolean`

### getScale()

```java
public float getScale()
```

**Returns:** `float`

### isEnabled()

```java
protected boolean isEnabled(T element)
```

Checks if an element should have events sent to it
* **Parameter `element`**: element to check


@return

**Returns:** `boolean`

### isElementHovered()

```java
public boolean isElementHovered(T element, double mouseX, double mouseY)
```

Checks if an element is hovered. Can be overridden to change the hover behavior.
* **Parameter `element`**: the element


**Parameter `mouseX`**: the x-coordinate of the mouse


**Parameter `mouseY`**: the y-coordinate of the mouse


**Returns**: true if the window is hovered



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

### shouldSerialize()

```java
public boolean shouldSerialize(boolean autosave)
```

**Returns:** `boolean`

---

Copyright (c) 2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
