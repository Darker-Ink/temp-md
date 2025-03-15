# ColorUtils

**Package:** `org.rusherhack.core.utils`

**Source:** `org/rusherhack/core/utils/ColorUtils.java`

Helper class containing color related functions
* **Author:** John200410



## Overview

`ColorUtils` is a class.

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| COLOR_MAP | `HashMap`<`String`[], `Color`> | public , static , final |


## Methods

### getRainbow()

```java
public , static Color getRainbow(long timeOffsetMs, float speed, float saturation, float brightness)
```

**Returns:** `Color`

### getRainbowRGB()

```java
public , static int getRainbowRGB(long timeOffsetMs, float speed, float saturation, float brightness)
```

Generates a rainbow color.
* **Parameter `timeOffsetMs`**: The time offset in milliseconds to start the rainbow effect.


**Parameter `speed`**: The speed of the rainbow effect.


**Parameter `saturation`**: The saturation value of the generated color (0.0 to 1.0).


**Parameter `brightness`**: The brightness value of the generated color (0.0 to 1.0).


**Returns**: An integer value representing the RGB color of the generated rainbow.



**Returns:** `int`

### getGradient()

```java
public , static Color getGradient(Color[] colors, long timeOffsetMs, float speed)
```

**Returns:** `Color`

### getGradientRGB()

```java
public , static int getGradientRGB(Color[] colors, long timeOffsetMs, float speed)
```

**Returns:** `int`

### getGradientRGB()

```java
public , static int getGradientRGB(int[] colors, long timeOffsetMs, float speed)
```

**Returns:** `int`

### blendColors()

```java
public , static int blendColors(int[] colors, float fraction)
```

**Returns:** `int`

### transparency()

```java
public , static Color transparency(Color c, int alpha)
```

**Returns:** `Color`

### transparency()

```java
public , static Color transparency(Color c, float alpha)
```

**Returns:** `Color`

### transparency()

```java
public , static int transparency(int c, int alpha)
```

**Returns:** `int`

### transparency()

```java
public , static int transparency(int c, float alpha)
```

**Returns:** `int`

### brightness()

```java
public , static int brightness(int c, float factor)
```

Does not use alpha

**Returns:** `int`

### getRGBA()

```java
public , static float[] getRGBA(int color)
```

**Returns:** `float`[]

### getHex()

```java
public , static int getHex(int red, int green, int blue, int alpha)
```

**Returns:** `int`

### interpolateColor()

```java
public , static int interpolateColor(int start, int end, double fraction)
```

**Returns:** `int`

### parseColor()

```java
public , static Color parseColor(String col)
```

Get a color from its name or color code
* **Parameter `col`**: color string


**Returns**: Color object



**Returns:** `Color`

---

Copyright (c) 2020-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
