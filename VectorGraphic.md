# VectorGraphic

**Package:** `org.rusherhack.client.api.render.graphic`

**Source:** `org/rusherhack/client/api/render/graphic/VectorGraphic.java`

A vector graphic
* **Author:** John200410 1/31/2023



## Overview

`VectorGraphic` is a class and implements [IGraphic](IGraphic.md).

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
| inputStream | `InputStream` | private , final |
| width | `int` | private , final |
| height | `int` | private , final |
| svgWidth | `int` | private |
| svgHeight | `int` | private |


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

**Returns:** `int`

### getHeight()

```java
public int getHeight()
```

**Returns:** `int`

### getXOffset()

```java
public int getXOffset()
```

**Returns:** `int`

### getYOffset()

```java
public int getYOffset()
```

**Returns:** `int`

### getSvgWidth()

```java
public int getSvgWidth()
```

**Returns:** `int`

### getSvgHeight()

```java
public int getSvgHeight()
```

**Returns:** `int`

### setSvgWidth()

```java
public void setSvgWidth(int svgWidth)
```

### setSvgHeight()

```java
public void setSvgHeight(int svgHeight)
```

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
