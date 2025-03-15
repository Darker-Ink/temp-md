# IInteractions

**Package:** `org.rusherhack.client.api.system`

**Source:** `org/rusherhack/client/api/system/IInteractions.java`

Interface for InteractionUtils
* **Author:** John200410 1/11/2024



## Overview

`IInteractions` is a interface.

## Methods

### placeBlock()

```java
 boolean placeBlock(BlockPos blockPos, InteractionHand hand, boolean raytrace)
```

Tries to place a block at the given position
* **Parameter `blockPos`**: @param hand


**Parameter `raytrace`**: **Returns**: false if unable to place a block at the given position





**Returns:** `boolean`

### useBlock()

```java
 boolean useBlock(BlockPos pos, InteractionHand hand, boolean strictDir, boolean raytrace)
```

Tries to right click a block
* **Parameter `pos`**: the position of the block


**Parameter `hand`**: the hand to use


**Parameter `raytrace`**: **Returns**: false if unable to use the block





**Returns:** `boolean`

### useBlock()

```java
 boolean useBlock(BlockHitResult hitResult, InteractionHand hand, boolean trySneaking)
```

Right clicks a block
* **Parameter `hitResult`**: the hit result of the block


**Parameter `hand`**: the hand to use


**Parameter `trySneaking`**: should be true if you are trying to place a block


**Returns**: true if the action was consumed



**Returns:** `boolean`

### getBlockPlaceHitResult()

```java
 BlockHitResult getBlockPlaceHitResult(BlockPos blockPos, boolean strictDir, boolean raytrace, double maxRange)
```

Calculates the best relative block that we can place on to place a block at the given position
* **Parameter `blockPos`**: The position we want to place the block


**Returns**: The best hit result



**Returns:** `BlockHitResult`

### getBlockHitResult()

```java
 BlockHitResult getBlockHitResult(BlockPos blockPos, boolean strictDir, boolean raytrace, double maxRange)
```

Calculates the best spot to reach a block
* **Parameter `blockPos`**: @param raytrace


**Parameter `maxRange`**: **Returns**: 




**Returns:** `BlockHitResult`

---

Copyright (c) 2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
