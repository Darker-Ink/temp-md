# ColorSetting

**Package:** `org.rusherhack.client.api.setting`

**Source:** `org/rusherhack/client/api/setting/ColorSetting.java`

**Author:** John200410 6/10/2023



## Overview

`ColorSetting` is a class that extends [Setting](Setting.md).

## Constructor

```java
public ColorSetting(String name, Color value)
```

```java
public ColorSetting(String name, String description, int value)
```

```java
public ColorSetting(String name, String description, Color value)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| rainbow | `boolean` | private |
| hasRainbowOption | `boolean` | private |
| rainbowMode | [RainbowMode](RainbowMode.md) | private |
| rainbowOffset | `int` | private |
| hasAlpha | `boolean` | private |
| themeSync | `boolean` | private |
| themeSyncAllowed | `boolean` | private |


## Methods

### getRealValue()

```java
public Color getRealValue()
```

**Returns:** `Color`

### getValue()

```java
public Color getValue()
```

**Returns:** `Color`

### getDisplayValue()

```java
public String getDisplayValue()
```

**Returns:** `String`

### getRainbowWithOffset()

```java
public int getRainbowWithOffset(int offset)
```

**Returns:** `int`

### getValueRGB()

```java
public int getValueRGB()
```

**Returns:** `int`

### isRainbow()

```java
public boolean isRainbow()
```

**Returns:** `boolean`

### setRainbow()

```java
public ColorSetting setRainbow(boolean rainbow)
```

**Returns:** [ColorSetting](ColorSetting.md)

### isRainbowAllowed()

```java
public boolean isRainbowAllowed()
```

**Returns:** `boolean`

### setRainbowAllowed()

```java
public ColorSetting setRainbowAllowed(boolean hasRainbowOption)
```

**Returns:** [ColorSetting](ColorSetting.md)

### getRainbowMode()

```java
public RainbowMode getRainbowMode()
```

**Returns:** [RainbowMode](RainbowMode.md)

### setRainbowMode()

```java
public void setRainbowMode(RainbowMode rainbowMode)
```

### getRainbowOffset()

```java
public int getRainbowOffset()
```

**Returns:** `int`

### setRainbowOffset()

```java
public void setRainbowOffset(int rainbowOffset)
```

### isAlphaAllowed()

```java
public boolean isAlphaAllowed()
```

**Returns:** `boolean`

### setAlphaAllowed()

```java
public ColorSetting setAlphaAllowed(boolean hasAlpha)
```

**Returns:** [ColorSetting](ColorSetting.md)

### isThemeSync()

```java
public boolean isThemeSync()
```

**Returns:** `boolean`

### setThemeSync()

```java
public ColorSetting setThemeSync(boolean themeSync)
```

**Returns:** [ColorSetting](ColorSetting.md)

### isThemeSyncAllowed()

```java
public boolean isThemeSyncAllowed()
```

**Returns:** `boolean`

### setThemeSyncAllowed()

```java
public ColorSetting setThemeSyncAllowed(boolean themeSyncAllowed)
```

**Returns:** [ColorSetting](ColorSetting.md)

### parseValue()

```java
public Color parseValue(String string, boolean set)
```

**Returns:** `Color`

### deserializeValue()

```java
public boolean deserializeValue(JsonElement json)
```

**Returns:** `boolean`

### serializeValue()

```java
public JsonElement serializeValue()
```

**Returns:** `JsonElement`

### setVisibility()

```java
public ColorSetting setVisibility(BooleanSupplier tester)
```

**Returns:** [ColorSetting](ColorSetting.md)

### setChangeAction()

```java
public ColorSetting setChangeAction(Runnable run)
```

**Returns:** [ColorSetting](ColorSetting.md)

### onChange()

```java
public ColorSetting onChange(Consumer<Color> consumer)
```

**Returns:** [ColorSetting](ColorSetting.md)

### getRed()

```java
public int getRed()
```

**Returns:** `int`

### setRed()

```java
public void setRed(int red)
```

### getGreen()

```java
public int getGreen()
```

**Returns:** `int`

### setGreen()

```java
public void setGreen(int green)
```

### getBlue()

```java
public int getBlue()
```

**Returns:** `int`

### setBlue()

```java
public void setBlue(int blue)
```

### getAlpha()

```java
public int getAlpha()
```

**Returns:** `int`

### setAlpha()

```java
public void setAlpha(int alpha)
```

### setAlphaAllowed()

```java
public void setAlphaAllowed(int alpha)
```

i fucked up and named it that by accident

### setHue()

```java
public void setHue(float hue)
```

**Parameter `hue`**: 0-1



### getHue()

```java
public float getHue()
```

**Returns:** `float`

### getSaturation()

```java
public float getSaturation()
```

**Returns:** `float`

### getBrightness()

```java
public float getBrightness()
```

**Returns:** `float`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
