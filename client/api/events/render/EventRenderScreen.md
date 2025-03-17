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
| mouseX | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private , final |
| mouseY | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private , final |
| partialTick | [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html) | private , final |


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

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### getMouseY()

```java
public int getMouseY()
```

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### getPartialTick()

```java
public float getPartialTick()
```

**Returns:** [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html)

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

