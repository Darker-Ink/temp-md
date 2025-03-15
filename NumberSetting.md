# NumberSetting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/NumberSetting.java`

**Author:** John200410 1/15/2023



## Overview

`NumberSetting` is a class that extends [Setting](Setting.md).

## Constructor

```java
public NumberSetting(String name, T value, T minimum, T maximum)
```

```java
public NumberSetting(String name, String description, T value, T minimum, T maximum)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| displayFormat | `DecimalFormat` | private , static , final |
| minimum | `T` | private , final |
| maximum | `T` | private , final |
| clampMinimum | `boolean` | private |
| clampMaximum | `boolean` | private |
| incrementing | `boolean` | private |
| incrementStep | `double` | private |


## Methods

### parseValue()

```java
public T parseValue(String string, boolean set)
```

**Returns:** `T`

### getDisplayValue()

```java
public String getDisplayValue()
```

**Returns:** `String`

### setValueObj()

```java
public void setValueObj(Object value)
```

### setValue()

```java
public void setValue(double d)
```

### setValue()

```java
public void setValue(double d, boolean clamp, boolean round)
```

### serializeValue()

```java
public JsonElement serializeValue()
```

**Returns:** `JsonElement`

### deserializeValue()

```java
public boolean deserializeValue(JsonElement json)
```

**Returns:** `boolean`

### getMinimum()

```java
public T getMinimum()
```

**Returns:** `T`

### getMaximum()

```java
public T getMaximum()
```

**Returns:** `T`

### clampMin()

```java
public NumberSetting<T> clampMin()
```

**Returns:** [NumberSetting](NumberSetting.md)<`T`>

### clampMax()

```java
public NumberSetting<T> clampMax()
```

**Returns:** [NumberSetting](NumberSetting.md)<`T`>

### incremental()

```java
public NumberSetting<T> incremental(double incrementStep)
```

**Returns:** [NumberSetting](NumberSetting.md)<`T`>

### setVisibility()

```java
public NumberSetting<T> setVisibility(BooleanSupplier tester)
```

**Returns:** [NumberSetting](NumberSetting.md)<`T`>

### setChangeAction()

```java
public NumberSetting<T> setChangeAction(Runnable run)
```

**Returns:** [NumberSetting](NumberSetting.md)<`T`>

### onChange()

```java
public NumberSetting<T> onChange(Consumer<T> consumer)
```

**Returns:** [NumberSetting](NumberSetting.md)<`T`>

### setHidden()

```java
public NumberSetting<T> setHidden(boolean hidden)
```

**Returns:** [NumberSetting](NumberSetting.md)<`T`>

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
