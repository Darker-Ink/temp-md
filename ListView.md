# ListView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/ListView.java`

**Author:** John200410



## Overview

`ListView` is a class that extends [WindowView](WindowView.md).

## Constructor

```java
public ListView(String name, Window window, List<T> items)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| itemView | [ListItemView](ListItemView.md) | private , final |
| items | `List`<`T`> | private , final |
| columns | `List`<[Column](Column.md)> | private , final |
| sortColumn | [Column](Column.md) | private |
| sortAscending | `boolean` | private |
| selectedItem | `T` | private |
| deleteCallback | `Consumer`<`T`> | private |


## Methods

### renderViewContent()

```java
public void renderViewContent(double mouseX, double mouseY)
```

### sortByColumn()

```java
public void sortByColumn(ListView<?>.Column column)
```

### resort()

```java
public void resort()
```

### getColumns()

```java
public List<Column> getColumns()
```

**Returns:** `List`<[Column](Column.md)>

### getColumnWidth()

```java
public double getColumnWidth(ListView<?>.Column column)
```

**Returns:** `double`

### getSortColumn()

```java
public Column getSortColumn()
```

**Returns:** [Column](Column.md)

### isSortAscending()

```java
public boolean isSortAscending()
```

**Returns:** `boolean`

### getSelectedItem()

```java
public T getSelectedItem()
```

**Returns:** `T`

### setSelectedItem()

```java
public void setSelectedItem(ListItemContent selectedItem)
```

### addColumn()

```java
public Column addColumn(String name)
```

**Returns:** [Column](Column.md)

### addColumn()

```java
public Column addColumn(String name, double widthWeight)
```

**Returns:** [Column](Column.md)

### addColumn()

```java
public Column addColumn(String name, Comparator<T> comparator, double widthWeight)
```

**Returns:** [Column](Column.md)

### getItemView()

```java
public ListItemView getItemView()
```

**Returns:** [ListItemView](ListItemView.md)

### setDeleteCallback()

```java
public void setDeleteCallback(Consumer<T> deleteCallback)
```

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
