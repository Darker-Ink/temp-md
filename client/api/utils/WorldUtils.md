# WorldUtils

**Package:** `org.rusherhack.client.api.utils`

**Source:** `org/rusherhack/client/api/utils/WorldUtils.java`

**Author:** John200410 6/18/2023



## Overview

`WorldUtils` is a class and implements [Globals](/client/api/Globals.md).

## Methods

### getEntities()

```java
public , static List<Entity> getEntities()
```

**Returns**: all loaded entities



**Returns:** `List`<`Entity`>

### getEntities()

```java
public , static List<Entity> getEntities(Predicate<Entity> predicate)
```

**Returns**: all loaded entities



**Returns:** `List`<`Entity`>

### getEntitiesSorted()

```java
public , static List<Entity> getEntitiesSorted()
```

**Returns**: all loaded entities sorted by distance to camera



**Returns:** `List`<`Entity`>

### getEntitiesSorted()

```java
public , static List<Entity> getEntitiesSorted(Entity entity)
```

**Returns**: all loaded entities sorted by distance to entity



**Returns:** `List`<`Entity`>

### getEntitiesSorted()

```java
public , static List<Entity> getEntitiesSorted(Entity entity, Predicate<Entity> predicate)
```

**Returns**: all loaded entities sorted by distance to entity



**Returns:** `List`<`Entity`>

### getChunks()

```java
public , static List<LevelChunk> getChunks()
```

**Returns:** `List`<`LevelChunk`>

### getBlockEntities()

```java
public , static List<BlockEntity> getBlockEntities(boolean sorted)
```

**Returns:** `List`<`BlockEntity`>

### getSphere()

```java
public , static List<BlockPos> getSphere(Vec3i center, float sphereRadius)
```

**Returns**: a sphere of block positions



**Returns:** `List`<`BlockPos`>

### getSphere()

```java
public , static List<BlockPos> getSphere(Vec3i center, float sphereRadius, Predicate<BlockPos> predicate)
```

**Parameter `predicate`**: a predicate for which all positions will be tested against


**Returns**: a sphere of block positions



**Returns:** `List`<`BlockPos`>

### getCircle()

```java
public , static List<BlockPos> getCircle(Vec3i center, float circleRadius)
```

**Returns**: a circle of block positions



**Returns:** `List`<`BlockPos`>

### isReplaceble()

```java
public , static boolean isReplaceble(BlockPos pos)
```

**Returns**: true if the position is air or contains a replaceable block



**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### checkCollision()

```java
public , static boolean checkCollision(BlockPos pos)
```

**Returns**: true if the position is free of entities that would prevent placing



**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### checkCollision()

```java
public , static boolean checkCollision(BlockPos pos, VoxelShape shape, Predicate<Entity> predicate)
```

**Parameter `shape`**: the shape in which we are checking for collision


**Parameter `predicate`**: a predicate for which all entities will be tested against


**Returns**: true if the position is free of entities that would prevent placing



**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

