# ISerializable

**Package:** `org.rusherhack.core.serialize`

**Source:** `org/rusherhack/core/serialize/ISerializable.java`

Interface for things that can be saved to disk
* **Author:** John200410



## Overview

`ISerializable` is a interface.

## Methods

### serialize()

```java
 T serialize()
```

**Returns:** `T`

### deserialize()

```java
 boolean deserialize(T obj)
```

Deserializes the given object
* **Parameter `obj`**: the object to deserialize


**Returns**: whether the deserialization was successful



**Returns:** `boolean`

### shouldSerialize()

```java
default boolean shouldSerialize(boolean autosave)
```

Whether this object should be serialized
* **Parameter `autosave`**: whether this is an autosave


**Returns**: whether this object should be serialized



**Returns:** `boolean`

### shouldAutoSave()

```java
default boolean shouldAutoSave()
```

**Returns:** `boolean`

---

Copyright (c) 2022-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
