# IPanelItem

**Package:** `org.rusherhack.client.api.ui.panel`

**Source:** `org/rusherhack/client/api/ui/panel/IPanelItem.java`

TODO: is this even needed

## Overview

`IPanelItem` is a interface that extends [IRenderable2D](IRenderable2D.md), [IClickable](IClickable.md), [ITypeable](ITypeable.md).

## Methods

### getWidth()

```java
 double getWidth()
```

**Returns:** `double`

### getHeight()

```java
 double getHeight(boolean total)
```

**Returns:** `double`

### isHovered()

```java
 boolean isHovered(double mouseX, double mouseY, boolean includeSubItems)
```

Alternative for ``#isHovered(double, double)
* **Parameter `mouseX`**: mouse x position


**Parameter `mouseY`**: mouse y position


**Parameter `includeSubItems`**: whether or not to include sub items in height calculation


**Returns**: whether or not the mouse is hovering over this item



**Returns:** `boolean`

### isHovered()

```java
default boolean isHovered(double mouseX, double mouseY)
```

**Returns:** `boolean`

### isVisible()

```java
default boolean isVisible()
```

**Returns:** `boolean`

---

Copyright (c) 2022-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
