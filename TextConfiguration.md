# TextConfiguration

**Package:** `org.rusherhack.client.api.config`

**Source:** `org/rusherhack/client/api/config/TextConfiguration.java`

**Author:** John200410 7/6/2023



## Overview

`TextConfiguration` is a class that extends [Configuration](Configuration.md).

## Constructor

```java
public TextConfiguration(File file)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| newLines | `boolean` | private |


## Methods

### createConfiguration()

```java
public , static TextConfiguration createConfiguration(String name)
```

**Returns:** [TextConfiguration](TextConfiguration.md)

### createConfiguration()

```java
public , static TextConfiguration createConfiguration(String parentDirectory, String name)
```

**Returns:** [TextConfiguration](TextConfiguration.md)

### write()

```java
public void write(ISerializable<?> serializable)
```

### read()

```java
public void read(ISerializable<?> serializable)
```

### allowNewLines()

```java
public TextConfiguration allowNewLines()
```

**Returns:** [TextConfiguration](TextConfiguration.md)

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
