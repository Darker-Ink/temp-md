# ModuleCategory

**Package:** `org.rusherhack.client.api.feature.module`

**Source:** `org/rusherhack/client/api/feature/module/ModuleCategory.java`

**Author:** John200410 1/16/2023



## Overview

`ModuleCategory` is a enum and implements [INamed](/core/interfaces/INamed.md).

## Constructor

```java
 ModuleCategory(String displayName)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| displayName | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private final |


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

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getDisplayName()

```java
public String getDisplayName()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getAliases()

```java
public String[] getAliases()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)[]

### getCategoryByName()

```java
public static ModuleCategory getCategoryByName(String name)
```

**Returns:** [ModuleCategory](/client/api/feature/module/ModuleCategory.md)

