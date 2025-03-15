# ThemeBase

**Package:** `org.rusherhack.client.api.ui.theme`

**Source:** `org/rusherhack/client/api/ui/theme/ThemeBase.java`

**Author:** John200410 2/23/2023



## Overview

`ThemeBase` is a class and implements [ITheme](ITheme.md).

## Constructor

```java
public ThemeBase(String name, String description, Color defaultColor)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | `String` | private , final |
| description | `String` | private , final |
| settings | `List`<[Setting](Setting.md)<`?`>> | private , final |
| color | [ColorSetting](ColorSetting.md) | private , final |


## Methods

### getName()

```java
public String getName()
```

**Returns:** `String`

### getDescription()

```java
public String getDescription()
```

**Returns:** `String`

### getSettings()

```java
public List<Setting<?>> getSettings()
```

**Returns:** `List`<[Setting](Setting.md)<`?`>>

### getColorSetting()

```java
public ColorSetting getColorSetting()
```

**Returns:** [ColorSetting](ColorSetting.md)

### getPrimaryColor()

```java
public Color getPrimaryColor()
```

**Returns:** `Color`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
