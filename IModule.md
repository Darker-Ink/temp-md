# IModule

**Package:** `org.rusherhack.client.api.feature.module`

**Source:** `org/rusherhack/client/api/feature/module/IModule.java`

A categorized feature with settings
* **Author:** John200410 1/15/2023



## Overview

`IModule` is a interface that extends [IFeatureConfigurable](IFeatureConfigurable.md), [INotifiable](INotifiable.md), [IHideable](IHideable.md), [JsonSerializable](JsonSerializable.md).

## Methods

### getCategory()

```java
 ModuleCategory getCategory()
```

**Returns**: Category of this module



**Returns:** [ModuleCategory](ModuleCategory.md)

### getMetadata()

```java
default String getMetadata()
```

**Returns**: A string containing additional information about a running module



**Returns:** `String`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
