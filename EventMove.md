# EventMove

**Package:** `org.rusherhack.client.api.events.player`

**Source:** `org/rusherhack/client/api/events/player/EventMove.java`

This event is called when the player is moving
* **Author:** John200410 6/14/2023



## Overview

`EventMove` is a class that extends `EventCancellable`.

## Constructor

```java
public EventMove(Vec3 motion)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| motionX | `double` | private |
| motionY | `double` | private |
| motionZ | `double` | private |


## Methods

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

### getMotion()

```java
public Vec3 getMotion()
```

**Returns:** `Vec3`

### setMotion()

```java
public void setMotion(Vec3 motion)
```

### setMotion()

```java
public void setMotion(double x, double y, double z)
```

### getPreferredStage()

```java
public Stage getPreferredStage()
```

**Returns:** `Stage`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
