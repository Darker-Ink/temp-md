# Setting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/Setting.java`

TODO: make getValue() return default value if the setting is not visible
* **Author:** John200410 1/15/2023



## Overview

`Setting` is a class and implements [IFeature](/core/feature/IFeature.md), [IHideable](/core/interfaces/IHideable.md), [JsonSerializable](/core/serialize/JsonSerializable.md).

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
| name | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private , final |
| displayName | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private |
| description | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private |
| value | `T` | private |
| defaultValue | `T` | private |
| hidden | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |
| subSettings | `List`<[Setting](/core/setting/Setting.md)<`?`>> | private , final |
| parent | [Setting](/core/setting/Setting.md)<`?`> | private |
| consumer | `Consumer`<`T`> | private |
| visibilityTest | `BooleanSupplier` | private |
| shouldSerialize | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |


## Methods

### getName()

```java
public String getName()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getDisplayName()

```java
public String getDisplayName()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getFullName()

```java
public String getFullName()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getDescription()

```java
public String getDescription()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

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

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

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



**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### reset()

```java
public void reset(boolean includeSubSettings)
```

### isHiddenByDefault()

```java
public boolean isHiddenByDefault()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### isHidden()

```java
public boolean isHidden()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### setHidden()

```java
public Setting<T> setHidden(boolean hidden)
```

**Returns:** [Setting](/core/setting/Setting.md)<`T`>

### addSubSettings()

```java
public void addSubSettings(Setting<?> settings)
```

### getSubSettings()

```java
public List<Setting<?>> getSubSettings()
```

**Returns:** `List`<[Setting](/core/setting/Setting.md)<`?`>>

### getAllSubSettings()

```java
public List<Setting<?>> getAllSubSettings()
```

**Returns:** `List`<[Setting](/core/setting/Setting.md)<`?`>>

### getSubSetting()

```java
public Setting<?> getSubSetting(String name)
```

**Returns:** [Setting](/core/setting/Setting.md)<`?`>

### getParent()

```java
public Setting<?> getParent()
```

**Returns:** [Setting](/core/setting/Setting.md)<`?`>

### setChangeAction()

```java
public Setting<T> setChangeAction(Runnable run)
```

**Returns:** [Setting](/core/setting/Setting.md)<`T`>

### onChange()

```java
public Setting<T> onChange(Consumer<T> consumer)
```

**Returns:** [Setting](/core/setting/Setting.md)<`T`>

### getConsumer()

```java
public Consumer<T> getConsumer()
```

**Returns:** `Consumer`<`T`>

### setVisibility()

```java
public Setting<T> setVisibility(BooleanSupplier tester)
```

**Returns:** [Setting](/core/setting/Setting.md)<`T`>

### setDescription()

```java
public Setting<T> setDescription(String description)
```

**Returns:** [Setting](/core/setting/Setting.md)<`T`>

### serialize()

```java
public JsonElement serialize()
```

**Returns:** `JsonElement`

### deserialize()

```java
public boolean deserialize(JsonElement jsonElement)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### shouldSerialize()

```java
public boolean shouldSerialize(boolean autosave)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### setShouldSerialize()

```java
public Setting<T> setShouldSerialize(boolean shouldSerialize)
```

**Returns:** [Setting](/core/setting/Setting.md)<`T`>

### deserializeValue()

```java
public , abstract boolean deserializeValue(JsonElement json)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

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

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

