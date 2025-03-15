# PanelHandlerBase

**Package:** `org.rusherhack.client.api.ui.panel`

**Source:** `org/rusherhack/client/api/ui/panel/PanelHandlerBase.java`

**Author:** John200410 1/13/2023



## Overview

`PanelHandlerBase` is a class that extends [ElementHandlerBase](ElementHandlerBase.md).

## Constructor

```java
public PanelHandlerBase(boolean scaledWithMinecraftGui)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| panels | `List`<`T`> | protected , final |


## Methods

### createPanel()

```java
public , abstract T createPanel(String name)
```

Instantiates a panel with the given name
* **Parameter `name`**: The name of the panel


**Returns**: The panel



**Returns:** `T`

### addPanel()

```java
public void addPanel(T panel)
```

Adds a panel to the list of panels
* @param panel

### moveElementToTop()

```java
public void moveElementToTop(T element)
```

### getElements()

```java
public List<T> getElements()
```

**Returns:** `List`<`T`>

### getFontRenderer()

```java
public IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](IFontRenderer.md)

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
