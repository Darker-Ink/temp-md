# PanelItemBase

**Package:** `org.rusherhack.client.api.ui.panel`

**Source:** `org/rusherhack/client/api/ui/panel/PanelItemBase.java`

**Author:** John200410 12/21/2022



## Overview

`PanelItemBase` is a class and implements [IPanelItem](/client/api/ui/panel/IPanelItem.md).

## Constructor

```java
public PanelItemBase(PanelBase<?> panel, T parent)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| panel | [PanelBase](/client/api/ui/panel/PanelBase.md)<`?`> | protected final |
| parent | `T` | protected final |
| subItems | [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<`T`> | protected final |


## Methods

### addSubItem()

```java
public void addSubItem(T item)
```

### getSubItemList()

```java
public List<T> getSubItemList()
```

**Returns:** [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<`T`>

### getPanel()

```java
public PanelBase<?> getPanel()
```

**Returns:** [PanelBase](/client/api/ui/panel/PanelBase.md)<`?`>

### getParent()

```java
public T getParent()
```

**Returns:** `T`

