# IMixinMultiPlayerGameMode

**Package:** `org.rusherhack.client.api.accessors.client`

**Source:** `org/rusherhack/client/api/accessors/client/IMixinMultiPlayerGameMode.java`

**Author:** John200410 7/28/2023



## Overview

`IMixinMultiPlayerGameMode` is a interface.

## Methods

### getConnection()

```java
 ClientPacketListener getConnection()
```

**Returns:** `ClientPacketListener`

### getDestroyBlockPos()

```java
 BlockPos getDestroyBlockPos()
```

**Returns:** `BlockPos`

### getDestroyProgress()

```java
 float getDestroyProgress()
```

**Returns:** `float`

### setDestroyProgress()

```java
 void setDestroyProgress(float destroyProgress)
```

### getDestroyDelay()

```java
 int getDestroyDelay()
```

**Returns:** `int`

### setDestroyDelay()

```java
 void setDestroyDelay(int destroyDelay)
```

### setIsDestroying()

```java
 void setIsDestroying(boolean isDestroying)
```

### invokeStartPrediction()

```java
 void invokeStartPrediction(ClientLevel level, PredictiveAction action)
```

### invokeEnsureHasSentCarriedItem()

```java
 void invokeEnsureHasSentCarriedItem()
```

### invokePerformUseItemOn()

```java
 InteractionResult invokePerformUseItemOn(LocalPlayer player, InteractionHand hand, BlockHitResult result)
```

**Returns:** `InteractionResult`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
