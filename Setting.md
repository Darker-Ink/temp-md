# Setting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/Setting.java`

TODO: make getValue() return default value if the setting is not visible
* **Author:** John200410 1/15/2023



## Overview

`Setting` is a class and implements [IFeature](IFeature.md), [IHideable](IHideable.md), [JsonSerializable](JsonSerializable.md).

## Constructor

```java
public Setting(String name, T value)
```

```java
public Setting(String name, String description, T value)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | `String` | private , final |
| displayName | `String` | private |
| description | `String` | private |
| value | `T` | private |
| defaultValue | `T` | private |
| hidden | `boolean` | private |
| subSettings | `List`<[Setting](Setting.md)<`?`>> | private , final |
| parent | [Setting](Setting.md)<`?`> | private |
| consumer | `Consumer`<`T`> | private |
| visibilityTest | `BooleanSupplier` | private |
| shouldSerialize | `boolean` | private |


## Methods

### getName()

```java
public String getName()
```

**Returns:** `String`

### getDisplayName()

```java
public String getDisplayName()
```

**Returns:** `String`

### getFullName()

```java
public String getFullName()
```

**Returns:** `String`

### getDescription()

```java
public String getDescription()
```

**Returns:** `String`

### setValue()

```java
public void setValue(T value)
```

### setValueObj()

```java
public void setValueObj(Object value)
```

### setDefaultValue()

```java
public void setDefaultValue(T value)
```

### parseValue()

```java
public , abstract T parseValue(String string, boolean set)
```

Parses a string into a value for this setting
**Parameter `string`**: String to parse


**Parameter `set`**: Whether to set the value if it is parsed successfully


**Returns**: The parsed value, null if it failed to parse



**Returns:** `T`

### getValue()

```java
public T getValue()
```

**Returns:** `T`

### getDisplayValue()

```java
public , abstract String getDisplayValue()
```

**Returns:** `String`

### getDefaultValue()

```java
public T getDefaultValue()
```

**Returns:** `T`

### reset()

```java
public boolean reset()
```

Resets this feature to it's default state
* **Returns**: true if the feature was reset



**Returns:** `boolean`

### reset()

```java
public void reset(boolean includeSubSettings)
```

### isHiddenByDefault()

```java
public boolean isHiddenByDefault()
```

**Returns:** `boolean`

### isHidden()

```java
public boolean isHidden()
```

**Returns:** `boolean`

### setHidden()

```java
public Setting<T> setHidden(boolean hidden)
```

**Returns:** [Setting](Setting.md)<`T`>

### addSubSettings()

```java
public void addSubSettings(Setting<?> settings)
```

### getSubSettings()

```java
public List<Setting<?>> getSubSettings()
```

**Returns:** `List`<[Setting](Setting.md)<`?`>>

### getAllSubSettings()

```java
public List<Setting<?>> getAllSubSettings()
```

**Returns:** `List`<[Setting](Setting.md)<`?`>>

### getSubSetting()

```java
public Setting<?> getSubSetting(String name)
```

**Returns:** [Setting](Setting.md)<`?`>

### getParent()

```java
public Setting<?> getParent()
```

**Returns:** [Setting](Setting.md)<`?`>

### setChangeAction()

```java
public Setting<T> setChangeAction(Runnable run)
```

**Returns:** [Setting](Setting.md)<`T`>

### onChange()

```java
public Setting<T> onChange(Consumer<T> consumer)
```

**Returns:** [Setting](Setting.md)<`T`>

### getConsumer()

```java
public Consumer<T> getConsumer()
```

**Returns:** `Consumer`<`T`>

### setVisibility()

```java
public Setting<T> setVisibility(BooleanSupplier tester)
```

**Returns:** [Setting](Setting.md)<`T`>

### setDescription()

```java
public Setting<T> setDescription(String description)
```

**Returns:** [Setting](Setting.md)<`T`>

### serialize()

```java
public JsonElement serialize()
```

**Returns:** `JsonElement`

### deserialize()

```java
public boolean deserialize(JsonElement jsonElement)
```

**Returns:** `boolean`

### shouldSerialize()

```java
public boolean shouldSerialize(boolean autosave)
```

**Returns:** `boolean`

### setShouldSerialize()

```java
public Setting<T> setShouldSerialize(boolean shouldSerialize)
```

**Returns:** [Setting](Setting.md)<`T`>

### deserializeValue()

```java
public , abstract boolean deserializeValue(JsonElement json)
```

**Returns:** `boolean`

### serializeValue()

```java
public , abstract JsonElement serializeValue()
```

**Returns:** `JsonElement`

### serializeSubSettings()

```java
private JsonElement serializeSubSettings()
```

**Returns:** `JsonElement`

### deserializeSubSettings()

```java
private boolean deserializeSubSettings(JsonElement subSettings)
```

**Returns:** `boolean`

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
