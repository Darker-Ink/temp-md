# EventPlayerUpdate

**Package:** `org.rusherhack.client.api.events.player`

**Source:** `org/rusherhack/client/api/events/player/EventPlayerUpdate.java`

This event is called when the game is preparing to send player updates to the server.



Used modify the player's position, rotation, and on-ground state for the tick. Player states revert after POST stage is posted.
* **Author:** John200410 6/2/2023



## Overview

`EventPlayerUpdate` is a class that extends `EventCancellable`.

## Constructor

```java
public EventPlayerUpdate(LocalPlayer player)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| player | `LocalPlayer` | private , final |
| yaw | `float` | private |
| pitch | `float` | private |
| x | `double` | private |
| y | `double` | private |
| z | `double` | private |
| onGround | `boolean` | private |
| horizontalCollision | `boolean` | private |


## Methods

### getPlayer()

```java
public LocalPlayer getPlayer()
```

**Returns:** `LocalPlayer`

### getYaw()

```java
public float getYaw()
```

**Returns:** `float`

### setYaw()

```java
public void setYaw(float yaw)
```

### getPitch()

```java
public float getPitch()
```

**Returns:** `float`

### setPitch()

```java
public void setPitch(float pitch)
```

### getX()

```java
public double getX()
```

**Returns:** `double`

### setX()

```java
public void setX(double x)
```

### getY()

```java
public double getY()
```

**Returns:** `double`

### setY()

```java
public void setY(double y)
```

### getZ()

```java
public double getZ()
```

**Returns:** `double`

### setZ()

```java
public void setZ(double z)
```

### isOnGround()

```java
public boolean isOnGround()
```

**Returns:** `boolean`

### setOnGround()

```java
public void setOnGround(boolean onGround)
```

### getHorizontalCollision()

```java
public boolean getHorizontalCollision()
```

**Returns:** `boolean`

### setHorizontalCollision()

```java
public void setHorizontalCollision(boolean horizontalCollision)
```

### getStage()

```java
public Stage getStage()
```

`Stage`#PRE - called before the client sends player update to server



`Stage`#POST - called at the end of the local player tick

**Returns:** `Stage`

### getPreferredStage()

```java
public Stage getPreferredStage()
```

**Returns:** `Stage`

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
