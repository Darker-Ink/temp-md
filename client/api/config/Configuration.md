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
| CONFIG_DIRECTORY | [Path](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/nio/file/Path.html) | public static final |
| logger | [ILogger](/core/logging/ILogger.md) | public final |
| file | [File](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/io/File.html) | private final |


## Methods

### write()

```java
public abstract void write(ISerializable<?> serializable)
```

### read()

```java
public abstract void read(ISerializable<?> serializable)
```

### getFile()

```java
public File getFile()
```

**Returns:** [File](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/io/File.html)

### createTempFile()

```java
protected File createTempFile()
```

**Returns:** [File](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/io/File.html)

