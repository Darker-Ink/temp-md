# PanelBase

**Package:** `org.rusherhack.client.api.ui.panel`

**Source:** `org/rusherhack/client/api/ui/panel/PanelBase.java`

Basic panel element that with items that can be clicked
* **Author:** John200410 12/17/2022



## Overview

`PanelBase` is a class that extends [ScaledElementBase](ScaledElementBase.md) and implements [IRenderable2D](IRenderable2D.md), [ITickable](ITickable.md), [IClickable](IClickable.md), [IScrollable](IScrollable.md), [ITypeable](ITypeable.md), [IHideable](IHideable.md), [JsonSerializable](JsonSerializable.md), [INamed](INamed.md).

## Constructor

```java
public PanelBase(PanelHandlerBase<? extends PanelBase<T>> handler, String name)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | `String` | private , final |
| visible | `boolean` | private |
| items | `List`<`T`> | protected , final |
| handler | [PanelHandlerBase](PanelHandlerBase.md) | protected , final |


## Methods

### createFeatureItem()

```java
public , abstract T createFeatureItem(IFeature feature)
```

Instantiates a new item for the given feature
* **Parameter `feature`**: likely a module or hud element


**Returns**: the item



**Returns:** `T`

### addItem()

```java
public T addItem(T item)
```

**Returns:** `T`

### addItem()

```java
public T addItem(IFeature feature)
```

**Returns:** `T`

### getItemList()

```java
public List<T> getItemList()
```

**Returns:** `List`<`T`>

### getName()

```java
public String getName()
```

**Returns:** `String`

### isHidden()

```java
public boolean isHidden()
```

**Returns:** `boolean`

### setVisible()

```java
public void setVisible(boolean visible)
```

### getRenderer()

```java
public IRenderer2D getRenderer()
```

**Returns:** [IRenderer2D](IRenderer2D.md)

### getFontRenderer()

```java
public IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](IFontRenderer.md)

### serialize()

```java
public JsonElement serialize()
```

**Returns:** `JsonElement`

### deserialize()

```java
public boolean deserialize(JsonElement obj)
```

**Returns:** `boolean`

---

Copyright (c) 2022-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
