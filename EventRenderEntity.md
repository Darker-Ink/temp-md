# EventRenderEntity

**Package:** `org.rusherhack.client.api.events.render`

**Source:** `org/rusherhack/client/api/events/render/EventRenderEntity.java`

**Author:** John200410 7/6/2023



## Overview

`EventRenderEntity` is a class that extends `EventCancellable`.

## Constructor

```java
public EventRenderEntity(Entity entity, double x, double y, double z, float rotationYaw, float partialTicks, PoseStack matrixStack, MultiBufferSource buffer, int packedLight)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| entity | `Entity` | private , final |
| x | `double` | private , final |
| y | `double` | private , final |
| z | `double` | private , final |
| rotationYaw | `float` | private , final |
| partialTicks | `float` | private , final |
| matrixStack | `PoseStack` | private , final |
| buffer | `MultiBufferSource` | private |
| packedLight | `int` | private , final |
| shouldRenderModel | `boolean` | private |


## Methods

### getPreferredStage()

```java
public Stage getPreferredStage()
```

**Returns:** `Stage`

### getStage()

```java
public Stage getStage()
```

**Returns:** `Stage`

### getEntity()

```java
public Entity getEntity()
```

**Returns:** `Entity`

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

### getZ()

```java
public double getZ()
```

**Returns:** `double`

### getRotationYaw()

```java
public float getRotationYaw()
```

**Returns:** `float`

### getPartialTicks()

```java
public float getPartialTicks()
```

**Returns:** `float`

### getMatrixStack()

```java
public PoseStack getMatrixStack()
```

**Returns:** `PoseStack`

### getBuffer()

```java
public MultiBufferSource getBuffer()
```

**Returns:** `MultiBufferSource`

### setBufferSource()

```java
public void setBufferSource(MultiBufferSource buffer)
```

Only applies during ON stage

### setRenderModel()

```java
public void setRenderModel(boolean shouldRenderModel)
```

### shouldRenderModel()

```java
public boolean shouldRenderModel()
```

**Returns:** `boolean`

### getPackedLight()

```java
public int getPackedLight()
```

**Returns:** `int`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
