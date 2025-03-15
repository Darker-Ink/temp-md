# ListItem

**Package:** `org.rusherhack.client.api.feature.hud`

**Source:** `org/rusherhack/client/api/feature/hud/ListHudElement.java`

An item that gets rendered in this list
* **Author:** John200410 12/14/2021



## Overview

`ListItem` is a class.

## Constructor

```java
public ListItem(ListHudElement parent)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| parent | [ListHudElement](ListHudElement.md) | private , final |
| animation | [Animation](Animation.md) | private , final |
| markedForRemoval | `boolean` | private |


## Methods

### getText()

```java
public , abstract Component getText()
```

**Returns**: The text that will represent this item



**Returns:** `Component`

### shouldRemove()

```java
public , abstract boolean shouldRemove()
```

**Returns**: the condition that must be met to remove this item



**Returns:** `boolean`

### readyForRemoval()

```java
private boolean readyForRemoval()
```

**Returns:** `boolean`

### getHeight()

```java
public double getHeight()
```

**Returns:** `double`

### getWidth()

```java
public double getWidth()
```

**Returns:** `double`

### render()

```java
public void render(RenderContext renderContext, int indexInList)
```

### tick()

```java
public void tick()
```

Updates the animation state of this item

### toString()

```java
public String toString()
```

**Returns:** `String`

### equals()

```java
public boolean equals(Object obj)
```

**Returns:** `boolean`

### getColor()

```java
public int getColor(int index)
```

**Returns:** `int`

### getAnimation()

```java
public Animation getAnimation()
```

**Returns:** [Animation](Animation.md)

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

### getParent()

```java
public ListHudElement getParent()
```

**Returns:** [ListHudElement](ListHudElement.md)

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
