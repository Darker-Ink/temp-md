# Animation

**Package:** `org.rusherhack.core.animation`

**Source:** `org/rusherhack/core/animation/Animation.java`

Animation object that can be used to animate a value and track it's progress
* **Author:** John200410 2/12/2023



## Overview

`Animation` is a class.

## Constructor

```java
public Animation()
```

```java
public Animation(Easing tween, long durationMs)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| tween | [Easing](Easing.md) | private |
| playing | `boolean` | private |
| reverse | `boolean` | private |
| loop | `boolean` | private |
| duration | `long` | private |
| lastTime | `long` | private |
| timePassed | `long` | private |
| progress | `double` | private |


## Methods

### get()

```java
public double get()
```

**Returns:** `double`

### play()

```java
public Animation play()
```

Start the animation

**Returns:** [Animation](Animation.md)

### restart()

```java
public Animation restart()
```

Restart the animation

**Returns:** [Animation](Animation.md)

### reverse()

```java
public Animation reverse()
```

Reverse the animation

**Returns:** [Animation](Animation.md)

### setLoop()

```java
public Animation setLoop(boolean loop)
```

**Returns:** [Animation](Animation.md)

### setDirection()

```java
public Animation setDirection(boolean reverse)
```

**Returns:** [Animation](Animation.md)

### setDuration()

```java
public Animation setDuration(long durationMs)
```

Set the animation duration in milliseconds
* **Parameter `durationMs`**: the duration in milliseconds



**Returns:** [Animation](Animation.md)

### setTween()

```java
public Animation setTween(Easing tween)
```

Set the animation tween

**Returns:** [Animation](Animation.md)

### isPlaying()

```java
public boolean isPlaying()
```

**Returns:** `boolean`

### isReversed()

```java
public boolean isReversed()
```

**Returns:** `boolean`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
