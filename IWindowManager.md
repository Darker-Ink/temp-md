# IWindowManager

**Package:** `org.rusherhack.client.api.system`

**Source:** `org/rusherhack/client/api/system/IWindowManager.java`

**Author:** John200410



## Overview

`IWindowManager` is a interface that extends [IFeatureManager](IFeatureManager.md).

## Methods

### moveToTop()

```java
 void moveToTop(Window window)
```

Moves the window to the top.
* @param window

### popupWindow()

```java
 void popupWindow(PopupWindow window)
```

### closePopup()

```java
 void closePopup(PopupWindow window)
```

### getRenderer()

```java
 IRenderer2D getRenderer()
```

**Returns:** [IRenderer2D](IRenderer2D.md)

### getFontRenderer()

```java
 IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](IFontRenderer.md)

### getWindowHandler()

```java
 WindowHandlerBase getWindowHandler()
```

**Returns:** [WindowHandlerBase](WindowHandlerBase.md)

### getFocusedWindow()

```java
default Window getFocusedWindow()
```

**Returns:** [Window](Window.md)

### getVisibleWindows()

```java
default List<Window> getVisibleWindows()
```

**Returns:** `List`<[Window](Window.md)>

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
