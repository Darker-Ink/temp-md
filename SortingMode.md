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
| comparator | `Comparator`<[ListItem](ListItem.md)> | public , final |


## Constants

### LEXICOGRAPHICAL

Arguments: Comparator.comparingDouble(m -> -m.getWidth())

### ALPHABETICAL

Arguments: Comparator.comparing(ListItem::toString)

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
