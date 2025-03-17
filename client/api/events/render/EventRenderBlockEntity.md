# EventRenderBlockEntity

**Package:** `org.rusherhack.client.api.events.render`

**Source:** `org/rusherhack/client/api/events/render/EventRenderBlockEntity.java`

**Author:** John200410 12/13/2023



## Overview

`EventRenderBlockEntity` is a class that extends `EventCancellable`.

## Constructor

```java
public EventRenderBlockEntity(BlockEntity blockEntity, float partialTicks, PoseStack poseStack, MultiBufferSource bufferSource)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| blockEntity | `BlockEntity` | private , final |
| partialTicks | [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html) | private , final |
| poseStack | `PoseStack` | private , final |
| bufferSource | `MultiBufferSource` | private |


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

### getBlockEntity()

```java
public BlockEntity getBlockEntity()
```

**Returns:** `BlockEntity`

### getPartialTicks()

```java
public float getPartialTicks()
```

**Returns:** [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html)

### getPoseStack()

```java
public PoseStack getPoseStack()
```

**Returns:** `PoseStack`

### getBufferSource()

```java
public MultiBufferSource getBufferSource()
```

**Returns:** `MultiBufferSource`

### setBufferSource()

```java
public void setBufferSource(MultiBufferSource bufferSource)
```

Only applies during ON stage

