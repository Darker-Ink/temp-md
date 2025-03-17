# BooleanSetting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/BooleanSetting.java`

**Author:** John200410 1/15/2023



## Overview

`BooleanSetting` is a class that extends [Setting](/core/setting/Setting.md).

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
| TRUE_ALIASES | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private static final |
| FALSE_ALIASES | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private static final |


## Methods

### deserializeValue()

```java
public boolean deserializeValue(JsonElement json)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### serializeValue()

```java
public JsonElement serializeValue()
```

**Returns:** `JsonElement`

### setVisibility()

```java
public BooleanSetting setVisibility(BooleanSupplier tester)
```

**Returns:** [BooleanSetting](/core/setting/BooleanSetting.md)

### parseValue()

```java
public Boolean parseValue(String string, boolean set)
```

**Returns:** [Boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### getDisplayValue()

```java
public String getDisplayValue()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### setChangeAction()

```java
public BooleanSetting setChangeAction(Runnable run)
```

**Returns:** [BooleanSetting](/core/setting/BooleanSetting.md)

### onChange()

```java
public BooleanSetting onChange(Consumer<Boolean> consumer)
```

**Returns:** [BooleanSetting](/core/setting/BooleanSetting.md)

### setHidden()

```java
public BooleanSetting setHidden(boolean hidden)
```

**Returns:** [BooleanSetting](/core/setting/BooleanSetting.md)

