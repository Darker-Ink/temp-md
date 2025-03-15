# INamed

**Package:** `org.rusherhack.core.interfaces`

**Source:** `org/rusherhack/core/interfaces/INamed.java`

**Author:** John200410



## Overview

`INamed` is a interface.

## Methods

### getName()

```java
 String getName()
```

**Returns:** `String`

### getDisplayName()

```java
default String getDisplayName()
```

**Returns:** `String`

### getAliases()

```java
default String[] getAliases()
```

Returns an array of accepted aliases for this object.



MUST include ``#getName().
* **Returns**: array of accepted aliases



**Returns:** `String`[]

---

Copyright (c) 2020-2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
