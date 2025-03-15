# IHudElement

**Package:** `org.rusherhack.client.api.feature.hud`

**Source:** `org/rusherhack/client/api/feature/hud/IHudElement.java`

Hud element interface
* **Author:** John200410 3/6/2023



## Overview

`IHudElement` is a interface that extends [IFeatureConfigurable](IFeatureConfigurable.md), [IRenderable2D](IRenderable2D.md), [IToggleable](IToggleable.md), [ITickable](ITickable.md), [IDraggable](IDraggable.md), [JsonSerializable](JsonSerializable.md).

## Methods

### renderContent()

```java
default void renderContent(RenderContext context, int mouseX, int mouseY)
```

DEPRECATED! Override ``#renderContent(RenderContext, double, double) instead.

### renderContent()

```java
default void renderContent(RenderContext context, double mouseX, double mouseY)
```

Hud element is being called for rendering.



Matrix is translated to the top left corner of the element before being called.

### shouldDrawBackground()

```java
default boolean shouldDrawBackground()
```

**Returns**: whether the background should be drawn



**Returns:** `boolean`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
