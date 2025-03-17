# StringSetting

**Package:** `org.rusherhack.core.setting`

**Source:** `org/rusherhack/core/setting/StringSetting.java`

**Author:** John200410 1/24/2023



## Overview

`StringSetting` is a class that extends [Setting](/core/setting/Setting.md).

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
| options | `LinkedHashSet`<[String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)> | private , final |
| isNameVisible | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |


## Methods

### getOptions()

```java
public LinkedHashSet<String> getOptions()
```

**Returns:** `LinkedHashSet`<[String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)>

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

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

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
public StringSetting setVisibility(BooleanSupplier tester)
```

**Returns:** [StringSetting](/core/setting/StringSetting.md)

### setChangeAction()

```java
public StringSetting setChangeAction(Runnable run)
```

**Returns:** [StringSetting](/core/setting/StringSetting.md)

### onChange()

```java
public StringSetting onChange(Consumer<String> consumer)
```

**Returns:** [StringSetting](/core/setting/StringSetting.md)

### setNameVisible()

```java
public StringSetting setNameVisible(boolean isNameVisible)
```

**Returns:** [StringSetting](/core/setting/StringSetting.md)

### isNameVisible()

```java
public boolean isNameVisible()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

