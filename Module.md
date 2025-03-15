# Module

**Package:** `org.rusherhack.client.api.feature.module`

**Source:** `org/rusherhack/client/api/feature/module/Module.java`

A base module with no implementation
* **Author:** John200410 1/16/2023



## Overview

`Module` is a class and implements [IModule](IModule.md), `EventListener`, [ILoggable](ILoggable.md), [Globals](Globals.md).

## Constructor

```java
public Module(String name, ModuleCategory category)
```

```java
public Module(String name, String description, ModuleCategory category)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| name | `String` | private , final |
| description | `String` | private , final |
| category | [ModuleCategory](ModuleCategory.md) | private , final |
| hidden | `boolean` | private |
| notifications | `boolean` | private |
| listening | `boolean` | private |
| settings | `List`<[Setting](Setting.md)<`?`>> | private , final |
| logger | [ILogger](ILogger.md) | protected , final |


## Methods

### getName()

```java
public String getName()
```

**Returns:** `String`

### getDescription()

```java
public String getDescription()
```

**Returns:** `String`

### getCategory()

```java
public ModuleCategory getCategory()
```

**Returns:** [ModuleCategory](ModuleCategory.md)

### sendNotification()

```java
public void sendNotification(NotificationType type, String message)
```

### sendNotification()

```java
public void sendNotification(NotificationType type, String message, int id)
```

### sendNotification()

```java
public void sendNotification(NotificationType type, Component component)
```

### sendNotification()

```java
public void sendNotification(NotificationType type, Component component, int id)
```

### registerSettings()

```java
public void registerSettings(Setting<?> settings)
```

### getSettings()

```java
public List<Setting<?>> getSettings()
```

**Returns:** `List`<[Setting](Setting.md)<`?`>>

### isHidden()

```java
public boolean isHidden()
```

TODO: this should not be the behavior

**Returns:** `boolean`

### setHidden()

```java
public void setHidden(boolean hidden)
```

### areNotificationsEnabled()

```java
public boolean areNotificationsEnabled()
```

**Returns:** `boolean`

### setNotifications()

```java
public void setNotifications(boolean notifications)
```

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

### isListening()

```java
public boolean isListening()
```

**Returns:** `boolean`

### setListening()

```java
public void setListening(boolean state)
```

### getLogger()

```java
public ILogger getLogger()
```

**Returns:** [ILogger](ILogger.md)

### createCommand()

```java
public ModuleCommand createCommand()
```

**Returns:** [ModuleCommand](ModuleCommand.md)

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
