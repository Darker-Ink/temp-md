# ICommandManager

**Package:** `org.rusherhack.core.command`

**Source:** `org/rusherhack/core/command/ICommandManager.java`

Interface for accessing the command manager
* **Author:** John200410 7/15/2024



## Overview

`ICommandManager` is a interface that extends [IFeatureManager](/core/feature/IFeatureManager.md).

## Methods

### getDispatcher()

```java
 ICommandDispatcher<?> getDispatcher()
```

**Returns**: the command dispatcher



**Returns:** [ICommandDispatcher](/core/command/dispatch/ICommandDispatcher.md)<`?`>

### getPrefix()

```java
 String getPrefix()
```

**Returns**: the command prefix



**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

