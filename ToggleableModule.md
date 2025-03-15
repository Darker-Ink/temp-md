# ToggleableModule

**Package:** `org.rusherhack.client.api.feature.module`

**Source:** `org/rusherhack/client/api/feature/module/ToggleableModule.java`

A module that can be toggled
* **Author:** John200410 1/17/2023



## Overview

`ToggleableModule` is a class that extends [Module](Module.md) and implements [IToggleable](IToggleable.md), [IBindable](IBindable.md).

## Constructor

```java
public ToggleableModule(String name, ModuleCategory category)
```

```java
public ToggleableModule(String name, String description, ModuleCategory category)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| toggled | `boolean` | private |


## Methods

### toggle()

```java
public void toggle()
```

### isToggled()

```java
public boolean isToggled()
```

**Returns:** `boolean`

### setToggled()

```java
public void setToggled(boolean toggled)
```

### onEnable()

```java
public void onEnable()
```

Called when the module is enabled.



Avoid referencing the world or player here, because modules can be toggled while they are null.

### onDisable()

```java
public void onDisable()
```

Called when the module is disabled.



Avoid referencing the world or player here, because modules can be toggled while they are null.

### onKeybindEvent()

```java
public void onKeybindEvent()
```

### getBindReference()

```java
public String getBindReference()
```

**Returns:** `String`

### isListening()

```java
public boolean isListening()
```

**Returns:** `boolean`

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

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
