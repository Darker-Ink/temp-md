# IServerState

**Package:** `org.rusherhack.client.api.system`

**Source:** `org/rusherhack/client/api/system/IServerState.java`


@author John200410**Author:** historian



## Overview

`IServerState` is a interface.

## Methods

### getTPS()

```java
default float getTPS()
```

Grabs the current average ticks per second
* **Returns**: the average ticks per second



**Returns:** `float`

### getTPS()

```java
 float getTPS(boolean clamped)
```

Grabs the current average ticks per second
* **Returns**: the average ticks per second



**Returns:** `float`

### getLastUpdate()

```java
 long getLastUpdate()
```

**Returns**: The last time the server sent a non-chat packet



**Returns:** `long`

### getServerIP()

```java
 String getServerIP()
```

**Returns**: A string representing the server IP



**Returns:** `String`

### isPlayerSprinting()

```java
 boolean isPlayerSprinting()
```

**Returns**: the last sprint state the player sent



**Returns:** `boolean`

### isPlayerSneaking()

```java
 boolean isPlayerSneaking()
```

**Returns**: the last sneak state the player sent



**Returns:** `boolean`

### getPlayerX()

```java
 double getPlayerX()
```

**Returns**: the last x position the player sent



**Returns:** `double`

### getPlayerY()

```java
 double getPlayerY()
```

**Returns**: the last y position the player sent



**Returns:** `double`

### getPlayerZ()

```java
 double getPlayerZ()
```

**Returns**: the last z position the player sent



**Returns:** `double`

### getPlayerYaw()

```java
 float getPlayerYaw()
```

**Returns:** `float`

### getPlayerPitch()

```java
 float getPlayerPitch()
```

**Returns**: the last pitch rotation the player sent



**Returns:** `float`

### getPlayerSlot()

```java
 int getPlayerSlot()
```

**Returns**: the last held item slot the player sent



**Returns:** `int`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
