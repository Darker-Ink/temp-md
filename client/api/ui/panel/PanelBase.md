# PanelBase

**Package:** `org.rusherhack.client.api.ui.panel`

**Source:** `org/rusherhack/client/api/ui/panel/PanelBase.java`

Basic panel element that with items that can be clicked
* **Author:** John200410 12/17/2022



## Overview

`PanelBase` is a class that extends [ScaledElementBase](/client/api/ui/ScaledElementBase.md) and implements [IRenderable2D](/client/api/render/IRenderable2D.md), [ITickable](/core/interfaces/ITickable.md), [IClickable](/core/interfaces/IClickable.md), [IScrollable](/core/interfaces/IScrollable.md), [ITypeable](/core/interfaces/ITypeable.md), [IHideable](/core/interfaces/IHideable.md), [JsonSerializable](/core/serialize/JsonSerializable.md), [INamed](/core/interfaces/INamed.md).

## Constructor

```java
public PanelBase(PanelHandlerBase<? extends PanelBase<T>> handler, String name)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private final |
| visible | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |
| items | `List`<`T`> | protected final |
| handler | [PanelHandlerBase](/client/api/ui/panel/PanelHandlerBase.md) | protected final |


## Methods

### createFeatureItem()

```java
public abstract T createFeatureItem(IFeature feature)
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

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### isHidden()

```java
public boolean isHidden()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### setVisible()

```java
public void setVisible(boolean visible)
```

### getRenderer()

```java
public IRenderer2D getRenderer()
```

**Returns:** [IRenderer2D](/client/api/render/IRenderer2D.md)

### getFontRenderer()

```java
public IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](/client/api/render/font/IFontRenderer.md)

### serialize()

```java
public JsonElement serialize()
```

**Returns:** `JsonElement`

### deserialize()

```java
public boolean deserialize(JsonElement obj)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

