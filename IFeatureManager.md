# IFeatureManager

**Package:** `org.rusherhack.core.feature`

**Source:** `org/rusherhack/core/feature/IFeatureManager.java`

Interface for feature management systems
* **Author:** John200410 1/17/2023



## Overview

`IFeatureManager` is a interface.

## Methods

### registerFeature()

```java
 void registerFeature(T feature)
```

Registers a new feature
* **Parameter `feature`**: feature to register



### getFeature()

```java
 Optional<T> getFeature(String name)
```

Attempts to find a feature given its name
* **Parameter `name`**: name of the feature


**Returns**: the feature



**Returns:** `Optional`<`T`>

### getFeatures()

```java
 Iterable<T> getFeatures()
```

**Returns**: registered features



**Returns:** `Iterable`<`T`>

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
