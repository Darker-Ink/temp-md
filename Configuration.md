# Configuration

**Package:** `org.rusherhack.client.api.config`

**Source:** `org/rusherhack/client/api/config/Configuration.java`

Utility class for serializing and deserializing objects to and from disk
* **Author:** John200410 1/24/2023



## Overview

`Configuration` is a class.

## Constructor

```java
public Configuration(File file)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| CONFIG_DIRECTORY | `Path` | public , static , final |
| logger | [ILogger](ILogger.md) | public , final |
| file | `File` | private , final |


## Methods

### write()

```java
public , abstract void write(ISerializable<?> serializable)
```

### read()

```java
public , abstract void read(ISerializable<?> serializable)
```

### getFile()

```java
public File getFile()
```

**Returns:** `File`

### createTempFile()

```java
protected File createTempFile()
```

**Returns:** `File`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
