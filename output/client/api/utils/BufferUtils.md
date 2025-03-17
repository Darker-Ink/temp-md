# BufferUtils

**Package:** `org.rusherhack.client.api.utils`

**Source:** `org/rusherhack/client/api/utils/BufferUtils.java`

**Author:** John200410 1/3/2023



## Overview

`BufferUtils` is a class.

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| ALLOCATOR | `MemoryUtil.MemoryAllocator` | public static final |


## Methods

### create()

```java
public static ByteBuffer create(int size)
```

**Returns:** `ByteBuffer`

### resize()

```java
public static ByteBuffer resize(ByteBuffer buffer, int size)
```

**Returns:** `ByteBuffer`

### fileToByteBuffer()

```java
public static ByteBuffer fileToByteBuffer(File file)
```

**Returns:** `ByteBuffer`

### resourceToByteBuffer()

```java
public static ByteBuffer resourceToByteBuffer(ClassLoader cl, String resource)
```

**Returns:** `ByteBuffer`

### inputStreamToByteBuffer()

```java
public static ByteBuffer inputStreamToByteBuffer(InputStream inputStream)
```

**Returns:** `ByteBuffer`

