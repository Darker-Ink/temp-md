# IMixinEntity

**Package:** `org.rusherhack.client.api.accessors.entity`

**Source:** `org/rusherhack/client/api/accessors/entity/IMixinEntity.java`

**Author:** John200410 7/5/2023



## Overview

`IMixinEntity` is a interface.

## Methods

### setOnGround()

```java
 void setOnGround(boolean onGround)
```

### getDimensions()

```java
 EntityDimensions getDimensions()
```

**Returns:** `EntityDimensions`

### getStuckSpeedMultiplier()

```java
 Vec3 getStuckSpeedMultiplier()
```

**Returns:** `Vec3`

### setStuckSpeedMultiplier()

```java
 void setStuckSpeedMultiplier(Vec3 stuckSpeedMultiplier)
```

### setTouchingWater()

```java
 void setTouchingWater(boolean touchingWater)
```

### callCollide()

```java
 Vec3 callCollide(Vec3 vec)
```

**Returns:** `Vec3`

### invokeGetSharedFlag()

```java
 boolean invokeGetSharedFlag(int flag)
```

**Returns:** `boolean`

### invokeSetSharedFlag()

```java
 void invokeSetSharedFlag(int flag, boolean value)
```

### invokeCalculateViewVector()

```java
 Vec3 invokeCalculateViewVector(float xRot, float yRot)
```

**Returns:** `Vec3`

### invokeCanAddPassenger()

```java
 boolean invokeCanAddPassenger(Entity entity)
```

**Returns:** `boolean`

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
