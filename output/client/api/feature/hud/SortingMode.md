# SortingMode

**Package:** `org.rusherhack.client.api.feature.hud`

**Source:** `org/rusherhack/client/api/feature/hud/ListHudElement.java`

## Overview

`SortingMode` is a enum.

## Constructor

```java
 SortingMode(Comparator<ListItem> comparator)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| comparator | `Comparator`<[ListItem](/client/api/feature/hud/ListItem.md)> | public final |


## Constants

### LEXICOGRAPHICAL

Arguments: Comparator.comparingDouble(m -> -m.getWidth())

### ALPHABETICAL

Arguments: Comparator.comparing(ListItem::toString)

