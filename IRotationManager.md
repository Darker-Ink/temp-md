# IRotationManager

**Package:** `org.rusherhack.client.api.system`

**Source:** `org/rusherhack/client/api/system/IRotationManager.java`

**Author:** John200410 7/6/2023



## Overview

`IRotationManager` is a interface.

## Methods

### updateRotation()

```java
default void updateRotation(Entity entity)
```

### updateRotation()

```java
 void updateRotation(Entity entity, float step)
```

### updateRotation()

```java
default void updateRotation(BlockPos blockPos)
```

### updateRotation()

```java
default void updateRotation(BlockPos blockPos, float step)
```

### updateRotation()

```java
 void updateRotation(BlockPos blockPos, Direction direction, float step)
```

### updateRotation()

```java
 void updateRotation(BlockHitResult hitResult, float step)
```

### updateRotation()

```java
default void updateRotation(float yaw, float pitch)
```

### updateRotation()

```java
 void updateRotation(float yaw, float pitch, float step)
```

### isLookingAt()

```java
 boolean isLookingAt(Entity entity)
```

**Returns:** `boolean`

### isLookingAt()

```java
default boolean isLookingAt(BlockHitResult hitResult)
```

**Returns:** `boolean`

### isLookingAt()

```java
default boolean isLookingAt(BlockHitResult hitResult, boolean checkDirection)
```

**Returns:** `boolean`

### isLookingAt()

```java
default boolean isLookingAt(BlockPos blockPos)
```

**Returns:** `boolean`

### isLookingAt()

```java
 boolean isLookingAt(BlockPos blockPos, Direction direction)
```

**Returns:** `boolean`

### getLookRaycast()

```java
 BlockHitResult getLookRaycast(BlockPos blockPos)
```

**Returns:** `BlockHitResult`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
