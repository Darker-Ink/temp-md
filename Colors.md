# Colors

**Package:** `org.rusherhack.client.api.system`

**Source:** `org/rusherhack/client/api/system/Colors.java`

Interface for grabbing the user's color preferences
* **Author:** John200410 6/16/2023



## Overview

`Colors` is a interface.

## Methods

### primaryColor()

```java
 ColorSetting primaryColor()
```

**Returns**: the primary theme color



**Returns:** [ColorSetting](ColorSetting.md)

### getRainbowColor()

```java
 int getRainbowColor(ColorSetting setting, int offsetMs)
```

Uses `org.rusherhack.core.utils.ColorUtils` to get either a rainbow or gradient color based on color preferences

**Returns:** `int`

### getEntityColor()

```java
 Color getEntityColor(Entity entity, ColorMode mode)
```

**Returns:** `Color`

### getBlockEntityColor()

```java
 Color getBlockEntityColor(BlockEntity tileEntity, ColorMode mode)
```

**Returns:** `Color`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
