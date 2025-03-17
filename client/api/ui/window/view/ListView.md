# ListView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/ListView.java`

**Author:** John200410



## Overview

`ListView` is a class that extends [WindowView](/client/api/ui/window/view/WindowView.md).

## Constructor

```java
public ListView(String name, Window window, List<T> items)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| itemView | [ListItemView](/client/api/ui/window/view/ListItemView.md) | private final |
| items | [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<`T`> | private final |
| columns | [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<[Column](/client/api/ui/window/view/Column.md)> | private final |
| sortColumn | [Column](/client/api/ui/window/view/Column.md) | private |
| sortAscending | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |
| selectedItem | `T` | private |
| deleteCallback | [Consumer](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/function/Consumer.html)<`T`> | private |


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

**Returns:** [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<[Column](/client/api/ui/window/view/Column.md)>

### getColumnWidth()

```java
public double getColumnWidth(ListView<?>.Column column)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getSortColumn()

```java
public Column getSortColumn()
```

**Returns:** [Column](/client/api/ui/window/view/Column.md)

### isSortAscending()

```java
public boolean isSortAscending()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

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

**Returns:** [Column](/client/api/ui/window/view/Column.md)

### addColumn()

```java
public Column addColumn(String name, double widthWeight)
```

**Returns:** [Column](/client/api/ui/window/view/Column.md)

### addColumn()

```java
public Column addColumn(String name, Comparator<T> comparator, double widthWeight)
```

**Returns:** [Column](/client/api/ui/window/view/Column.md)

### getItemView()

```java
public ListItemView getItemView()
```

**Returns:** [ListItemView](/client/api/ui/window/view/ListItemView.md)

### setDeleteCallback()

```java
public void setDeleteCallback(Consumer<T> deleteCallback)
```

