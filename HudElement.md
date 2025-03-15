# HudElement

**Package:** `org.rusherhack.client.api.feature.hud`

**Source:** `org/rusherhack/client/api/feature/hud/HudElement.java`

A hud element is a draggable [ElementBase](ElementBase.md) that can be rendered on the screen.
* **Author:** John200410 3/15/2023



## Overview

`HudElement` is a class that extends [ScaledElementBase](ScaledElementBase.md) and implements [IHudElement](IHudElement.md), [IBindable](IBindable.md), `EventListener`, [ILoggable](ILoggable.md), [Globals](Globals.md).

## Constructor

```java
public HudElement(String name)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | `String` | private , final |
| toggled | `boolean` | private |
| description | `String` | private |
| settings | `List`<[Setting](Setting.md)<`?`>> | private , final |
| snapPoint | [SnapPoint](SnapPoint.md) | private |
| alignment | [Alignment](Alignment.md) | protected |
| dragging | `boolean` | private |
| dragDeltaX | `double` | private |
| dragDeltaY | `double` | private |
| logger | [ILogger](ILogger.md) | protected , final |


## Methods

### render()

```java
public void render(RenderContext context, double mouseX, double mouseY)
```

### correctPosition()

```java
protected void correctPosition(Alignment old, Alignment newAlignment)
```

### postRender()

```java
public void postRender(RenderContext context, double mouseX, double mouseY)
```

Some stuff shouldn't be rendered in nanovg context

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

### isDragging()

```java
public boolean isDragging()
```

**Returns:** `boolean`

### isHovered()

```java
public boolean isHovered(double mouseX, double mouseY)
```

**Returns:** `boolean`

### toggle()

```java
public void toggle()
```

### onEnable()

```java
public void onEnable()
```

### onDisable()

```java
public void onDisable()
```

### getBindReference()

```java
public String getBindReference()
```

**Returns:** `String`

### onKeybindEvent()

```java
public void onKeybindEvent()
```

### getLogger()

```java
public ILogger getLogger()
```

**Returns:** [ILogger](ILogger.md)

### isToggled()

```java
public boolean isToggled()
```

**Returns:** `boolean`

### setToggled()

```java
public void setToggled(boolean toggled)
```

### isListening()

```java
public boolean isListening()
```

**Returns:** `boolean`

### setX()

```java
public void setX(double x)
```

### setY()

```java
public void setY(double y)
```

### getX()

```java
public double getX()
```

**Returns:** `double`

### getY()

```java
public double getY()
```

**Returns:** `double`

### getStartX()

```java
public double getStartX()
```

**Returns:** `double`

### getStartY()

```java
public double getStartY()
```

**Returns:** `double`

### setStartX()

```java
public void setStartX(double x)
```

### setStartY()

```java
public void setStartY(double y)
```

### getScale()

```java
public double getScale()
```

**Returns:** `double`

### getFontRenderer()

```java
public IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](IFontRenderer.md)

### getSnapPoint()

```java
public SnapPoint getSnapPoint()
```

**Returns:** [SnapPoint](SnapPoint.md)

### setSnapPoint()

```java
public void setSnapPoint(SnapPoint snapPoint)
```

### serialize()

```java
public JsonElement serialize()
```

**Returns:** `JsonElement`

### deserialize()

```java
public boolean deserialize(JsonElement jsonElement)
```

**Returns:** `boolean`

### shouldUpdateAlignment()

```java
public boolean shouldUpdateAlignment()
```

**Returns:** `boolean`

### getAlignment()

```java
public Alignment getAlignment()
```

**Returns:** [Alignment](Alignment.md)

### calculateAlignment()

```java
public , static Alignment calculateAlignment(HudElement element)
```

**Returns:** [Alignment](Alignment.md)

### calculateAlignment()

```java
public , static Alignment calculateAlignment(double x, double y)
```

**Returns:** [Alignment](Alignment.md)

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
