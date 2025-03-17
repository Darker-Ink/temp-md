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



**Returns:** [ITheme](/client/api/ui/theme/ITheme.md)

### getClickGuiTheme()

```java
 ITheme getClickGuiTheme()
```

**Returns**: The theme currently being used by the ClickGUI



**Returns:** [ITheme](/client/api/ui/theme/ITheme.md)

### getHudTheme()

```java
 ITheme getHudTheme()
```

**Returns**: The theme currently being used by the HUD



**Returns:** [ITheme](/client/api/ui/theme/ITheme.md)

### getWindowsTheme()

```java
 ITheme getWindowsTheme()
```

**Returns**: The theme currently being used by Windows



**Returns:** [ITheme](/client/api/ui/theme/ITheme.md)

### getClickGuiHandler()

```java
default PanelHandlerBase<?> getClickGuiHandler()
```

**Returns:** [PanelHandlerBase](/client/api/ui/panel/PanelHandlerBase.md)<`?`>

### getHudHandler()

```java
default HudHandlerBase getHudHandler()
```

**Returns:** [HudHandlerBase](/client/api/ui/hud/HudHandlerBase.md)

### getWindowHandler()

```java
default WindowHandlerBase getWindowHandler()
```

**Returns:** [WindowHandlerBase](/client/api/ui/window/WindowHandlerBase.md)

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

**Returns:** [ITheme](/client/api/ui/theme/ITheme.md)

