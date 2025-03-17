# VectorGraphic

**Package:** `org.rusherhack.client.api.render.graphic`

**Source:** `org/rusherhack/client/api/render/graphic/VectorGraphic.java`

A vector graphic
* **Author:** John200410 1/31/2023



## Overview

`VectorGraphic` is a class and implements [IGraphic](/client/api/render/graphic/IGraphic.md).

## Constructor

```java
public VectorGraphic(String path, int width, int height)
```

```java
public VectorGraphic(InputStream inputStream, int width, int height)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| inputStream | [InputStream](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/io/InputStream.html) | private final |
| width | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private final |
| height | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private final |
| svgWidth | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private |
| svgHeight | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private |


## Methods

### getInputStream()

```java
public InputStream getInputStream()
```

**Returns:** [InputStream](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/io/InputStream.html)

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

### getSvgWidth()

```java
public int getSvgWidth()
```

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### getSvgHeight()

```java
public int getSvgHeight()
```

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### setSvgWidth()

```java
public void setSvgWidth(int svgWidth)
```

### setSvgHeight()

```java
public void setSvgHeight(int svgHeight)
```

