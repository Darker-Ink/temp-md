# NullSetting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/NullSetting.java`

Setting to be used for placeholders
* **Author:** John200410 1/24/2023



## Overview

`NullSetting` is a class that extends [Setting](/core/setting/Setting.md).

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

**Returns:** [Object](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Object.html)

### getDisplayValue()

```java
public String getDisplayValue()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

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
public NullSetting setVisibility(BooleanSupplier tester)
```

**Returns:** [NullSetting](/core/setting/NullSetting.md)

