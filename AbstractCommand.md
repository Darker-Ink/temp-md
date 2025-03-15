# AbstractCommand

**Package:** `org.rusherhack.core.command`

**Source:** `org/rusherhack/core/command/AbstractCommand.java`

**Author:** John200410



## Overview

`AbstractCommand` is a class and implements [IFeature](IFeature.md), [IHideable](IHideable.md).

## Constructor

```java
public AbstractCommand(String name, String description)
```

**Parameter `name`**: base name of the command


**Parameter `description`**: description of what the command does



## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | `String` | private , final |
| description | `String` | private , final |
| aliases | `List`<`String`> | private , final |


## Methods

### addAliases()

```java
public void addAliases(String aliases)
```

Add aliases to the command

### getName()

```java
public String getName()
```

**Returns**: name of the command



**Returns:** `String`

### getDisplayName()

```java
public String getDisplayName()
```

**Returns:** `String`

### getDescription()

```java
public String getDescription()
```

**Returns:** `String`

### getAliases()

```java
public String[] getAliases()
```

**Returns:** `String`[]

### isHidden()

```java
public boolean isHidden()
```

**Returns:** `boolean`

---

Copyright (c) 2020-2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
