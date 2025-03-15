# Timer

**Package:** `org.rusherhack.core.utils`

**Source:** `org/rusherhack/core/utils/Timer.java`

A simple timer
* **Author:** John200410



## Overview

`Timer` is a class.

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| time | `long` | private |


## Methods

### reset()

```java
public void reset()
```

Resets the timer

### passed()

```java
public boolean passed(double ms)
```

Checks if the timer has reached the specified time
* **Parameter `ms`**: time in milliseconds


**Returns**: true if the timer has reached the specified time



**Returns:** `boolean`

### ticksPassed()

```java
public boolean ticksPassed(int gameTicks)
```

Checks if the timer has reached the specified time
* **Parameter `gameTicks`**: time in minecraft game ticks (20 ticks = 1 second)


**Returns**: true if the timer has reached the specified time



**Returns:** `boolean`

### getTime()

```java
public long getTime()
```

**Returns**: how long this timer has been active in milliseconds



**Returns:** `long`

### getTicksPassed()

```java
public int getTicksPassed()
```

**Returns**: how long this timer has been active in game ticks (20 ticks per second)



**Returns:** `int`

### setTime()

```java
public void setTime(long time)
```

---

Copyright (c) 2020-2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
