# BindSetting

**Package:** `org.rusherhack.client.api.setting`

**Source:** `org/rusherhack/client/api/setting/BindSetting.java`

**Author:** John200410 5/10/2023



## Overview

`BindSetting` is a class that extends [Setting](Setting.md).

## Constructor

```java
public BindSetting(String name, IKey value)
```

```java
public BindSetting(String name, String description, IKey value)
```

## Methods

### parseValue()

```java
public IKey parseValue(String string, boolean set)
```

**Returns:** [IKey](IKey.md)

### getDisplayValue()

```java
public String getDisplayValue()
```

**Returns:** `String`

### deserializeValue()

```java
public boolean deserializeValue(JsonElement json)
```

**Returns:** `boolean`

### serializeValue()

```java
public JsonElement serializeValue()
```

**Returns:** `JsonElement`

### setVisibility()

```java
public BindSetting setVisibility(BooleanSupplier tester)
```

**Returns:** [BindSetting](BindSetting.md)

### setChangeAction()

```java
public BindSetting setChangeAction(Runnable run)
```

**Returns:** [BindSetting](BindSetting.md)

### onChange()

```java
public BindSetting onChange(Consumer<IKey> consumer)
```

**Returns:** [BindSetting](BindSetting.md)

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
