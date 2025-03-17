# PlayerUtils

**Package:** `org.rusherhack.client.api.utils`

**Source:** `org/rusherhack/client/api/utils/PlayerUtils.java`

Helper class containing player related functions
* **Author:** John200410 6/5/2023



## Overview

`PlayerUtils` is a class and implements [Globals](/client/api/Globals.md).

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| fallDistance | [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html) | private static |


## Methods

### getDirectionalSpeed()

```java
public static double[] getDirectionalSpeed(double speed)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)[]

### getDirectionalSpeed()

```java
public static double[] getDirectionalSpeed(float yaw, double speed)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)[]

### getDirectionalSpeed()

```java
public static double[] getDirectionalSpeed(LocalPlayer player, float yaw, double speed)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)[]

### getDirectionalSpeed()

```java
public static double[] getDirectionalSpeed(LocalPlayer player, float yaw, double speed, float forward, float strafe)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)[]

### hasHorizontalInput()

```java
public static boolean hasHorizontalInput()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### getEyeBlockPos()

```java
public static BlockPos getEyeBlockPos()
```

**Returns:** `BlockPos`

### getFallDistance()

```java
public static float getFallDistance()
```

**Returns:** [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html)

### onMove()

```java
private static void onMove(EventMove event)
```

