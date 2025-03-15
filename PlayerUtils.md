# PlayerUtils

**Package:** `org.rusherhack.client.api.utils`

**Source:** `org/rusherhack/client/api/utils/PlayerUtils.java`

Helper class containing player related functions
* **Author:** John200410 6/5/2023



## Overview

`PlayerUtils` is a class and implements [Globals](Globals.md).

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| fallDistance | `float` | private , static |


## Methods

### getDirectionalSpeed()

```java
public , static double[] getDirectionalSpeed(double speed)
```

**Returns:** `double`[]

### getDirectionalSpeed()

```java
public , static double[] getDirectionalSpeed(float yaw, double speed)
```

**Returns:** `double`[]

### getDirectionalSpeed()

```java
public , static double[] getDirectionalSpeed(LocalPlayer player, float yaw, double speed)
```

**Returns:** `double`[]

### getDirectionalSpeed()

```java
public , static double[] getDirectionalSpeed(LocalPlayer player, float yaw, double speed, float forward, float strafe)
```

**Returns:** `double`[]

### hasHorizontalInput()

```java
public , static boolean hasHorizontalInput()
```

**Returns:** `boolean`

### getEyeBlockPos()

```java
public , static BlockPos getEyeBlockPos()
```

**Returns:** `BlockPos`

### getFallDistance()

```java
public , static float getFallDistance()
```

**Returns:** `float`

### onMove()

```java
private , static void onMove(EventMove event)
```

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
