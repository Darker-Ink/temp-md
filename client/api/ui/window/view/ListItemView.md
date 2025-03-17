# ListItemView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/ListView.java`

## Overview

`ListItemView` is a class that extends [ScrollableView](/client/api/ui/window/view/ScrollableView.md).

## Constructor

```java
public ListItemView(Window window, ListView<T> listView, List<T> items)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| listView | [ListView](/client/api/ui/window/view/ListView.md)<`T`> | private , final |


## Methods

### keyTyped()

```java
public boolean keyTyped(int key, int scanCode, int modifiers)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### getListView()

```java
public ListView<T> getListView()
```

**Returns:** [ListView](/client/api/ui/window/view/ListView.md)<`T`>

### getWidth()

```java
public double getWidth()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getHeight()

```java
public double getHeight()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

