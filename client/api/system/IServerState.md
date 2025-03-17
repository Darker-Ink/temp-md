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



**Returns:** [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html)

### getTPS()

```java
 float getTPS(boolean clamped)
```

Grabs the current average ticks per second
* **Returns**: the average ticks per second



**Returns:** [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html)

### getLastUpdate()

```java
 long getLastUpdate()
```

**Returns**: The last time the server sent a non-chat packet



**Returns:** [long](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Long.html)

### getServerIP()

```java
 String getServerIP()
```

**Returns**: A string representing the server IP



**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### isPlayerSprinting()

```java
 boolean isPlayerSprinting()
```

**Returns**: the last sprint state the player sent



**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### isPlayerSneaking()

```java
 boolean isPlayerSneaking()
```

**Returns**: the last sneak state the player sent



**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### getPlayerX()

```java
 double getPlayerX()
```

**Returns**: the last x position the player sent



**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getPlayerY()

```java
 double getPlayerY()
```

**Returns**: the last y position the player sent



**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getPlayerZ()

```java
 double getPlayerZ()
```

**Returns**: the last z position the player sent



**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getPlayerYaw()

```java
 float getPlayerYaw()
```

**Returns:** [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html)

### getPlayerPitch()

```java
 float getPlayerPitch()
```

**Returns**: the last pitch rotation the player sent



**Returns:** [float](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Float.html)

### getPlayerSlot()

```java
 int getPlayerSlot()
```

**Returns**: the last held item slot the player sent



**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

