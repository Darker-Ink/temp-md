# IThemeManager

**Package:** `org.rusherhack.client.api.ui.theme`

**Source:** `org/rusherhack/client/api/ui/theme/IThemeManager.java`

Interface for accessing the theme manager
* **Author:** John200410 9/3/2023



## Overview

`IThemeManager` is a interface.

## Methods

### registerTheme()

```java
 void registerTheme(ITheme theme)
```

Registers a new theme
* **Parameter `theme`**: the theme



### getDefaultTheme()

```java
 ITheme getDefaultTheme()
```

**Returns**: The default "Classic" theme



**Returns:** [ITheme](ITheme.md)

### getClickGuiTheme()

```java
 ITheme getClickGuiTheme()
```

**Returns**: The theme currently being used by the ClickGUI



**Returns:** [ITheme](ITheme.md)

### getHudTheme()

```java
 ITheme getHudTheme()
```

**Returns**: The theme currently being used by the HUD



**Returns:** [ITheme](ITheme.md)

### getWindowsTheme()

```java
 ITheme getWindowsTheme()
```

**Returns**: The theme currently being used by Windows



**Returns:** [ITheme](ITheme.md)

### getClickGuiHandler()

```java
default PanelHandlerBase<?> getClickGuiHandler()
```

**Returns:** [PanelHandlerBase](PanelHandlerBase.md)<`?`>

### getHudHandler()

```java
default HudHandlerBase getHudHandler()
```

**Returns:** [HudHandlerBase](HudHandlerBase.md)

### getWindowHandler()

```java
default WindowHandlerBase getWindowHandler()
```

**Returns:** [WindowHandlerBase](WindowHandlerBase.md)

### getClickGuiScreen()

```java
 Screen getClickGuiScreen()
```

**Returns:** `Screen`

### getHudEditorScreen()

```java
 Screen getHudEditorScreen()
```

**Returns:** `Screen`

### getWindowsScreen()

```java
 Screen getWindowsScreen()
```

**Returns:** `Screen`

### getCurrentTheme()

```java
default ITheme getCurrentTheme()
```

**Returns:** [ITheme](ITheme.md)

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
