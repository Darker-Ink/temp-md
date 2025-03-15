# Logger

**Package:** `org.rusherhack.core.logging`

**Source:** `org/rusherhack/core/logging/Logger.java`

TODO: implement slf4j Logger interface
* **Author:** John200410 3/11/2023



## Overview

`Logger` is a class and implements [ILogger](ILogger.md).

## Constructor

```java
public Logger(String name)
```

```java
public Logger(String name, Path logDirectory)
```

```java
public Logger(String name, ILogger parentLogger)
```

```java
public Logger(String name, ILogger parentLogger, Path logDirectory)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | `String` | private , final |
| parentLogger | [ILogger](ILogger.md) | private , final |
| outputs | `List`<[ILog](ILog.md)> | protected , final |


## Methods

### info()

```java
public void info(String message)
```

### warn()

```java
public void warn(String message)
```

### error()

```java
public void error(String message)
```

### debug()

```java
public void debug(String message)
```

### log()

```java
public void log(String msg)
```

### getName()

```java
public String getName()
```

**Returns:** `String`

### getParent()

```java
public ILogger getParent()
```

**Returns:** [ILogger](ILogger.md)

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
