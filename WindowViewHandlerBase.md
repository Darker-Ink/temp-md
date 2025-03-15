# WindowViewHandlerBase

**Package:** `org.rusherhack.client.api.ui.window`

**Source:** `org/rusherhack/client/api/ui/window/WindowViewHandlerBase.java`

## Overview

`WindowViewHandlerBase` is a class.

## Constructor

```java
public WindowViewHandlerBase(WindowHandlerBase windowHandler)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| windowHandler | [WindowHandlerBase](WindowHandlerBase.md) | protected , final |


## Methods

### handleRenderViewContent()

```java
public void handleRenderViewContent(WindowView view, double mouseX, double mouseY)
```

Wrapper for [WindowView](WindowView.md)#renderViewContent(double, double) so custom things can be added
* **Parameter `view`**: @param mouseX


@param mouseY

### handleViewMouseClicked()

```java
public boolean handleViewMouseClicked(WindowView view, double mouseX, double mouseY, int button)
```

**Returns:** `boolean`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
