# ITheme

**Package:** `org.rusherhack.client.api.ui.theme`

**Source:** `org/rusherhack/client/api/ui/theme/ITheme.java`

Interface for creating themes.



A theme is a feature which changes the look and feel of the menus.
* **Author:** John200410 2/23/2023



## Overview

`ITheme` is a interface that extends [IFeatureConfigurable](IFeatureConfigurable.md), [JsonSerializable](JsonSerializable.md).

## Methods

### initialize()

```java
default void initialize()
```

Called when rusherhack is finished loading, and the theme should be initialized.

### getClickGuiHandler()

```java
default PanelHandlerBase<?> getClickGuiHandler()
```

This theme's ClickGUI handler
* **Returns**: panel handler for the ClickGUI, or null if this theme does not have a ClickGUI



**Returns:** [PanelHandlerBase](PanelHandlerBase.md)<`?`>

### getHudHandler()

```java
default HudHandlerBase getHudHandler()
```

This theme's HUD handler
* **Returns**: the hud handler, or null if this theme does not have a HUD



**Returns:** [HudHandlerBase](HudHandlerBase.md)

### getWindowHandler()

```java
default WindowHandlerBase getWindowHandler()
```

This theme's window handler
* **Returns**: the window handler, or null if this theme does not have a window handler



**Returns:** [WindowHandlerBase](WindowHandlerBase.md)

### getColorSetting()

```java
 ColorSetting getColorSetting()
```

**Returns**: The ColorSetting for this theme



**Returns:** [ColorSetting](ColorSetting.md)

### getPrimaryColor()

```java
default Color getPrimaryColor()
```

**Returns:** `Color`

### serialize()

```java
default JsonElement serialize()
```

**Returns:** `JsonElement`

### deserialize()

```java
default boolean deserialize(JsonElement jsonElement)
```

**Returns:** `boolean`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
