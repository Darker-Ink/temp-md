# IRenderer2D

**Package:** `org.rusherhack.client.api.render`

**Source:** `org/rusherhack/client/api/render/IRenderer2D.java`

**Author:** John200410 12/29/2022



## Overview

`IRenderer2D` is a interface that extends [IRenderer](IRenderer.md), [IScissorable](IScissorable.md).

## Methods

### begin()

```java
default void begin(PoseStack matrixStack)
```

### begin()

```java
default void begin(PoseStack matrixStack, IFontRenderer fontRenderer)
```

### getFontRenderer()

```java
 IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](IFontRenderer.md)

### drawRectangle()

```java
default void drawRectangle(double x, double y, double width, double height, int color)
```

### drawGradientRectangle()

```java
 void drawGradientRectangle(double x, double y, double endX, double endY, double width, double height, int startColor, int endColor)
```

### drawRectangleOutline()

```java
default void drawRectangleOutline(double x, double y, double width, double height, float outlineThickness, int color)
```

### drawOutlinedRectangle()

```java
default void drawOutlinedRectangle(double x, double y, double width, double height, float outlineThickness, int color, int outlineColor)
```

### _drawRectangle()

```java
 void _drawRectangle(double x, double y, double width, double height, boolean fill, boolean outline, float outlineThickness, int fillColor, int outlineColor)
```

### _drawRoundedRectangle()

```java
 void _drawRoundedRectangle(double x, double y, double width, double height, double radius, boolean fill, boolean outline, float outlineThickness, int fillColor, int outlineColor)
```

### drawTriangle()

```java
default void drawTriangle(double x, double y, double size, double theta, int color)
```

### drawTriangleOutline()

```java
default void drawTriangleOutline(double x, double y, double size, double theta, float outlineThickness, int color)
```

### drawOutlinedTriangle()

```java
default void drawOutlinedTriangle(double x, double y, double size, double theta, float outlineThickness, int color, int outlineColor)
```

### _drawTriangle()

```java
 void _drawTriangle(double x, double y, double size, double theta, boolean fill, boolean outline, float outlineThickness, int fillColor, int outlineColor)
```

### drawCircle()

```java
default void drawCircle(double x, double y, double radius, int color)
```

### drawCircleOutline()

```java
default void drawCircleOutline(double x, double y, double radius, float outlineThickness, int color)
```

### drawOutlinedCircle()

```java
default void drawOutlinedCircle(double x, double y, double radius, float outlineThickness, int color, int outlineColor)
```

### _drawCircle()

```java
default void _drawCircle(double x, double y, double radius, boolean fill, boolean outline, float outlineThickness, int fillColor, int outlineColor)
```

### _drawEllipse()

```java
 void _drawEllipse(double x, double y, double radiusX, double radiusY, boolean fill, boolean outline, float outlineThickness, int fillColor, int outlineColor)
```

### drawLine()

```java
 void drawLine(double x1, double y1, double x2, double y2, float thickness, int color)
```

### drawGraphicRectangle()

```java
default void drawGraphicRectangle(IGraphic graphic, double x, double y, double width, double height)
```

### _drawGraphicRectangle()

```java
 void _drawGraphicRectangle(IGraphic graphic, double x, double y, double width, double height, double roundedRadius)
```

### _drawTextureRectangle()

```java
 void _drawTextureRectangle(int openGlTextureID, int textureWidth, int textureHeight, double x, double y, double width, double height, double roundedRadius)
```

### queue()

```java
 void queue(Runnable runnable)
```

### flushQueue()

```java
 void flushQueue()
```

---

Copyright (c) 2022-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
