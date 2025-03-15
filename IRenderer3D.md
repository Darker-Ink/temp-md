# IRenderer3D

**Package:** `org.rusherhack.client.api.render`

**Source:** `org/rusherhack/client/api/render/IRenderer3D.java`

TODO: possibly add drawQuad methods? drawVerticalQuad, drawHorizontalQuad, drawVerticalHorizontalQuad, draw HorizontalVerticalQuad
TODO: billboarding
TODO: render text
* **Author:** John200410 5/30/2023



## Overview

`IRenderer3D` is a interface that extends [IRenderer](IRenderer.md).

## Methods

### drawShape()

```java
 void drawShape(VoxelShape shape, double x, double y, double z, boolean fill, boolean outline, int fillColor)
```

### drawLine()

```java
default void drawLine(Vec3 start, Vec3 end, int color)
```

### drawLine()

```java
 void drawLine(double x1, double y1, double z1, double x2, double y2, double z2, int color)
```

### lineStrip()

```java
default void lineStrip(Vec3 point, int color)
```

### lineStrip()

```java
 void lineStrip(double x, double y, double z, int color)
```

### drawPlane()

```java
 void drawPlane(double x, double y, double z, double width, double height, Direction direction, boolean fill, boolean outline, int fillColor)
```

### drawBox()

```java
 void drawBox(BlockPos pos, boolean fill, boolean outline, int fillColor)
```

### drawBox()

```java
 void drawBox(Entity entity, float partialTicks, boolean fill, boolean outline, int fillColor)
```

### drawBox()

```java
 void drawBox(double x, double y, double z, double width, double height, double depth, boolean fill, boolean outline, int fillColor)
```

### setDepthTest()

```java
 void setDepthTest(boolean depthTest)
```

### setLineWidth()

```java
 void setLineWidth(float lineWidth)
```

### getQuadsBuffer()

```java
 BufferBuilder getQuadsBuffer()
```

**Returns:** `BufferBuilder`

### getLinesBuffer()

```java
 BufferBuilder getLinesBuffer()
```

**Returns:** `BufferBuilder`

### getLineStripBuffer()

```java
 BufferBuilder getLineStripBuffer()
```

**Returns:** `BufferBuilder`

### getTrianglesBuffer()

```java
 BufferBuilder getTrianglesBuffer()
```

**Returns:** `BufferBuilder`

### getTriangleFanBuffer()

```java
 BufferBuilder getTriangleFanBuffer()
```

**Returns:** `BufferBuilder`

### projectToScreen()

```java
 Vec2 projectToScreen(Vec3 pos)
```

**Returns**: null if the position is off screen



**Returns:** `Vec2`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
