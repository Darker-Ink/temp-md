# EnumSetting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/EnumSetting.java`

**Author:** John200410 1/24/2023



## Overview

`EnumSetting` is a class that extends [Setting](Setting.md).

## Constructor

```java
public EnumSetting(String name, T value)
```

```java
public EnumSetting(String name, String description, T value)
```

## Methods

### parseValue()

```java
public T parseValue(String string, boolean set)
```

**Returns:** `T`

### increment()

```java
public void increment()
```

### decrement()

```java
public void decrement()
```

### getOptions()

```java
public String[] getOptions(boolean displayName)
```

**Returns:** `String`[]

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
public EnumSetting<T> setVisibility(BooleanSupplier tester)
```

**Returns:** [EnumSetting](EnumSetting.md)<`T`>

### setChangeAction()

```java
public EnumSetting<T> setChangeAction(Runnable run)
```

**Returns:** [EnumSetting](EnumSetting.md)<`T`>

### onChange()

```java
public EnumSetting<T> onChange(Consumer<T> consumer)
```

**Returns:** [EnumSetting](EnumSetting.md)<`T`>

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
