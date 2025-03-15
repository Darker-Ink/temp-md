# CommandException

**Package:** `org.rusherhack.core.command.exceptions`

**Source:** `org/rusherhack/core/command/exceptions/CommandException.java`

**Author:** John200410 5/14/2024



## Overview

`CommandException` is a class that extends `Exception`.

## Constructor

```java
public CommandException(String message)
```

```java
public CommandException(String message, Throwable cause)
```

```java
public CommandException(String message, CommandProcessingSink context)
```

```java
public CommandException(String message, CommandProcessingSink context, Throwable cause)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| context | `CommandProcessingSink` | private |


## Methods

### setContext()

```java
public void setContext(CommandProcessingSink context)
```

### getContext()

```java
public CommandProcessingSink getContext()
```

**Returns:** `CommandProcessingSink`

### shouldPrintSyntax()

```java
public boolean shouldPrintSyntax()
```

**Returns:** `boolean`

---

Copyright (c) 2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
