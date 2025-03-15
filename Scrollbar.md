# Scrollbar

**Package:** `org.rusherhack.client.api.utils.objects`

**Source:** `org/rusherhack/client/api/utils/objects/Scrollbar.java`

Object to keep track of scroll offsets, animation, and clamp.
* **Author:** John200410 2/18/2023



## Overview

`Scrollbar` is a class.

## Constructor

```java
public Scrollbar(Animation animation)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| animation | [Animation](Animation.md) | private , final |
| scrollOffset | `double` | private |
| targetScrollOffset | `double` | private |


## Methods

### update()

```java
public void update()
```

### clamp()

```java
public void clamp(boolean strict, double min, double max)
```

### setScrollOffset()

```java
public void setScrollOffset(double scrollOffset)
```

### scroll()

```java
public void scroll(double delta)
```

### scroll()

```java
public void scroll(double delta, boolean animated)
```

### getScrollOffset()

```java
public double getScrollOffset()
```

**Returns:** `double`

### getRenderHeight()

```java
public double getRenderHeight(double viewLength, double contentLength)
```

**Returns:** `double`

### getRenderHeight()

```java
public double getRenderHeight(double viewLength, double contentLength, double trackLength)
```

**Returns:** `double`

### getRenderOffset()

```java
public double getRenderOffset(double viewLength, double contentLength)
```

**Returns:** `double`

### getRenderOffset()

```java
public double getRenderOffset(double viewLength, double contentLength, double trackLength)
```

**Returns:** `double`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
