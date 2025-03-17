# AbstractCommand

**Package:** `org.rusherhack.core.command`

**Source:** `org/rusherhack/core/command/AbstractCommand.java`

**Author:** John200410



## Overview

`AbstractCommand` is a class and implements [IFeature](/core/feature/IFeature.md), [IHideable](/core/interfaces/IHideable.md).

## Constructor

```java
public AbstractCommand(String name, String description)
```

**Parameter `name`**: base name of the command


**Parameter `description`**: description of what the command does



## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private final |
| description | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private final |
| aliases | `List`<[String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)> | private final |


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



**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getDisplayName()

```java
public String getDisplayName()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getDescription()

```java
public String getDescription()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getAliases()

```java
public String[] getAliases()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)[]

### isHidden()

```java
public boolean isHidden()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

