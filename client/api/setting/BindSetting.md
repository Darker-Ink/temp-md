# BindSetting

**Package:** `org.rusherhack.client.api.setting`

**Source:** `org/rusherhack/client/api/setting/BindSetting.java`

**Author:** John200410 5/10/2023



## Overview

`BindSetting` is a class that extends [Setting](/core/setting/Setting.md).

## Constructor

```java
public BindSetting(String name, IKey value)
```

```java
public BindSetting(String name, String description, IKey value)
```

## Methods

### parseValue()

```java
public IKey parseValue(String string, boolean set)
```

**Returns:** [IKey](/core/bind/key/IKey.md)

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
public BindSetting setVisibility(BooleanSupplier tester)
```

**Returns:** [BindSetting](/client/api/setting/BindSetting.md)

### setChangeAction()

```java
public BindSetting setChangeAction(Runnable run)
```

**Returns:** [BindSetting](/client/api/setting/BindSetting.md)

### onChange()

```java
public BindSetting onChange(Consumer<IKey> consumer)
```

**Returns:** [BindSetting](/client/api/setting/BindSetting.md)

