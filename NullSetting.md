# NullSetting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/NullSetting.java`

Setting to be used for placeholders
* **Author:** John200410 1/24/2023



## Overview

`NullSetting` is a class that extends [Setting](Setting.md).

## Constructor

```java
public NullSetting(String name)
```

```java
public NullSetting(String name, String description)
```

## Methods

### parseValue()

```java
public Object parseValue(String string, boolean set)
```

**Returns:** `Object`

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
public NullSetting setVisibility(BooleanSupplier tester)
```

**Returns:** [NullSetting](NullSetting.md)

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
