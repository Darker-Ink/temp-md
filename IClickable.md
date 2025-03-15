# IClickable

**Package:** `org.rusherhack.core.interfaces`

**Source:** `org/rusherhack/core/interfaces/IClickable.java`

## Overview

`IClickable` is a interface that extends [IHoverable](IHoverable.md).

## Methods

### mouseClicked()

```java
 boolean mouseClicked(double mouseX, double mouseY, int button)
```

Called when a mouse button is clicked
* **Parameter `button`**: mouse button that was clicked


**Returns**: if the click was consumed



**Returns:** `boolean`

### mouseReleased()

```java
default void mouseReleased(double mouseX, double mouseY, int button)
```

Called when a mouse button is released
* **Parameter `button`**: mouse button that was released



---

Copyright (c) 2022-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
