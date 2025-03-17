# JsonConfiguration

**Package:** `org.rusherhack.client.api.config`

**Source:** `org/rusherhack/client/api/config/JsonConfiguration.java`

**Author:** John200410 1/24/2023



## Overview

`JsonConfiguration` is a class that extends [Configuration](/client/api/config/Configuration.md).

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

**Returns:** [JsonConfiguration](/client/api/config/JsonConfiguration.md)

### createConfiguration()

```java
public , static JsonConfiguration createConfiguration(String parentDirectory, String name)
```

**Returns:** [JsonConfiguration](/client/api/config/JsonConfiguration.md)

### write()

```java
public void write(ISerializable<?> serializable)
```

### read()

```java
public void read(ISerializable<?> serializable)
```

