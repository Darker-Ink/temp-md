# StringSetting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/StringSetting.java`

**Author:** John200410 1/24/2023



## Overview

`StringSetting` is a class that extends [Setting](Setting.md).

## Constructor

```java
public StringSetting(String name, String value)
```

```java
public StringSetting(String name, String description, String value)
```

```java
public StringSetting(String name, String description, String value, String options)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| options | `LinkedHashSet`<`String`> | private , final |
| isNameVisible | `boolean` | private |


## Methods

### getOptions()

```java
public LinkedHashSet<String> getOptions()
```

**Returns:** `LinkedHashSet`<`String`>

### addOptions()

```java
public void addOptions(String options)
```

### setValue()

```java
public void setValue(String value)
```

### parseValue()

```java
public String parseValue(String string, boolean set)
```

**Returns:** `String`

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
public StringSetting setVisibility(BooleanSupplier tester)
```

**Returns:** [StringSetting](StringSetting.md)

### setChangeAction()

```java
public StringSetting setChangeAction(Runnable run)
```

**Returns:** [StringSetting](StringSetting.md)

### onChange()

```java
public StringSetting onChange(Consumer<String> consumer)
```

**Returns:** [StringSetting](StringSetting.md)

### setNameVisible()

```java
public StringSetting setNameVisible(boolean isNameVisible)
```

**Returns:** [StringSetting](StringSetting.md)

### isNameVisible()

```java
public boolean isNameVisible()
```

**Returns:** `boolean`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
