# TextureGraphic

**Package:** `org.rusherhack.client.api.render.graphic`

**Source:** `org/rusherhack/client/api/render/graphic/TextureGraphic.java`

**Author:** John200410 1/31/2023



## Overview

`TextureGraphic` is a class and implements [IGraphic](/client/api/render/graphic/IGraphic.md).

## Constructor

```java
public TextureGraphic(String path, int width, int height)
```

```java
public TextureGraphic(InputStream inputStream, int width, int height)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| inputStream | `InputStream` | private , final |
| u | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private , final |
| v | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private , final |
| width | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private , final |
| height | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private , final |


## Methods

### getInputStream()

```java
public InputStream getInputStream()
```

**Returns:** `InputStream`

### getWidth()

```java
public int getWidth()
```

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### getHeight()

```java
public int getHeight()
```

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### getXOffset()

```java
public int getXOffset()
```

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### getYOffset()

```java
public int getYOffset()
```

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

