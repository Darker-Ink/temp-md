# EventRenderScreen

**Package:** `org.rusherhack.client.api.events.render`

**Source:** `org/rusherhack/client/api/events/render/EventRenderScreen.java`

**Author:** John200410 7/27/2023



## Overview

`EventRenderScreen` is a class that extends `EventCancellable`.

## Constructor

```java
public EventRenderScreen(Screen screen, GuiGraphics graphics, int mouseX, int mouseY, float partialTick)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| screen | `Screen` | private , final |
| graphics | `GuiGraphics` | private , final |
| mouseX | `int` | private , final |
| mouseY | `int` | private , final |
| partialTick | `float` | private , final |


## Methods

### getScreen()

```java
public Screen getScreen()
```

**Returns:** `Screen`

### getGraphics()

```java
public GuiGraphics getGraphics()
```

**Returns:** `GuiGraphics`

### getMatrixStack()

```java
public PoseStack getMatrixStack()
```

**Returns:** `PoseStack`

### getMouseX()

```java
public int getMouseX()
```

**Returns:** `int`

### getMouseY()

```java
public int getMouseY()
```

**Returns:** `int`

### getPartialTick()

```java
public float getPartialTick()
```

**Returns:** `float`

### getStage()

```java
public Stage getStage()
```

**Returns**: PRE, ON, or POST



**Returns:** `Stage`

### getPreferredStage()

```java
public Stage getPreferredStage()
```

**Returns:** `Stage`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
