# BooleanSetting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/BooleanSetting.java`

**Author:** John200410 1/15/2023



## Overview

`BooleanSetting` is a class that extends [Setting](Setting.md).

## Constructor

```java
public BooleanSetting(String name, Boolean value)
```

```java
public BooleanSetting(String name, String description, Boolean value)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| TRUE_ALIASES | `String` | private , static , final |
| FALSE_ALIASES | `String` | private , static , final |


## Methods

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
public BooleanSetting setVisibility(BooleanSupplier tester)
```

**Returns:** [BooleanSetting](BooleanSetting.md)

### parseValue()

```java
public Boolean parseValue(String string, boolean set)
```

**Returns:** `Boolean`

### getDisplayValue()

```java
public String getDisplayValue()
```

**Returns:** `String`

### setChangeAction()

```java
public BooleanSetting setChangeAction(Runnable run)
```

**Returns:** [BooleanSetting](BooleanSetting.md)

### onChange()

```java
public BooleanSetting onChange(Consumer<Boolean> consumer)
```

**Returns:** [BooleanSetting](BooleanSetting.md)

### setHidden()

```java
public BooleanSetting setHidden(boolean hidden)
```

**Returns:** [BooleanSetting](BooleanSetting.md)

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
