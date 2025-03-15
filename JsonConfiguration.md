# JsonConfiguration

**Package:** `org.rusherhack.client.api.config`

**Source:** `org/rusherhack/client/api/config/JsonConfiguration.java`

**Author:** John200410 1/24/2023



## Overview

`JsonConfiguration` is a class that extends [Configuration](Configuration.md).

## Constructor

```java
public JsonConfiguration(File file)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| GSON | `Gson` | public , static , final |


## Methods

### createConfiguration()

```java
public , static JsonConfiguration createConfiguration(String name)
```

**Returns:** [JsonConfiguration](JsonConfiguration.md)

### createConfiguration()

```java
public , static JsonConfiguration createConfiguration(String parentDirectory, String name)
```

**Returns:** [JsonConfiguration](JsonConfiguration.md)

### write()

```java
public void write(ISerializable<?> serializable)
```

### read()

```java
public void read(ISerializable<?> serializable)
```

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
