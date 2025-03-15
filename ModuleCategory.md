# ModuleCategory

**Package:** `org.rusherhack.client.api.feature.module`

**Source:** `org/rusherhack/client/api/feature/module/ModuleCategory.java`

**Author:** John200410 1/16/2023



## Overview

`ModuleCategory` is a enum and implements [INamed](INamed.md).

## Constructor

```java
 ModuleCategory(String displayName)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| displayName | `String` | private , final |


## Constants

### CHAT

Arguments: "Chat"

### COMBAT

Arguments: "Combat"

### MISC

Arguments: "Miscellaneous"

### MOVEMENT

Arguments: "Movement"

### PLAYER

Arguments: "Player"

### RENDER

Arguments: "Render"

### WORLD

Arguments: "World"

### CLIENT

Arguments: "Client"

## Methods

### getName()

```java
public String getName()
```

**Returns:** `String`

### getDisplayName()

```java
public String getDisplayName()
```

**Returns:** `String`

### getAliases()

```java
public String[] getAliases()
```

**Returns:** `String`[]

### getCategoryByName()

```java
public , static ModuleCategory getCategoryByName(String name)
```

**Returns:** [ModuleCategory](ModuleCategory.md)

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
