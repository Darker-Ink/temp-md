# InputBuilder

**Package:** `org.rusherhack.client.api.utils`

**Source:** `org/rusherhack/client/api/utils/InputBuilder.java`

Class for modifying `net.minecraft.world.entity.player.Input` objects
* **Author:** john@rusherhack.org 12/28/2024



## Overview

`InputBuilder` is a class.

## Constructor

```java
public InputBuilder()
```

```java
public InputBuilder(Input input)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| forward | `boolean` | private |
| backward | `boolean` | private |
| left | `boolean` | private |
| right | `boolean` | private |
| jump | `boolean` | private |
| shift | `boolean` | private |
| sprint | `boolean` | private |


## Methods

### forward()

```java
public InputBuilder forward(boolean forward)
```

**Returns:** [InputBuilder](InputBuilder.md)

### backward()

```java
public InputBuilder backward(boolean backward)
```

**Returns:** [InputBuilder](InputBuilder.md)

### left()

```java
public InputBuilder left(boolean left)
```

**Returns:** [InputBuilder](InputBuilder.md)

### right()

```java
public InputBuilder right(boolean right)
```

**Returns:** [InputBuilder](InputBuilder.md)

### jump()

```java
public InputBuilder jump(boolean jump)
```

**Returns:** [InputBuilder](InputBuilder.md)

### shift()

```java
public InputBuilder shift(boolean shift)
```

**Returns:** [InputBuilder](InputBuilder.md)

### sprint()

```java
public InputBuilder sprint(boolean sprint)
```

**Returns:** [InputBuilder](InputBuilder.md)

### build()

```java
public Input build()
```

**Returns:** `Input`

---

Copyright (c) 2024-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
