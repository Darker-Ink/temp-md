# Module

**Package:** `org.rusherhack.client.api.feature.module`

**Source:** `org/rusherhack/client/api/feature/module/Module.java`

A base module with no implementation
* **Author:** John200410 1/16/2023



## Overview

`Module` is a class and implements [IModule](/client/api/feature/module/IModule.md), `EventListener`, [ILoggable](/core/logging/ILoggable.md), [Globals](/client/api/Globals.md).

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
| name | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private , final |
| description | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private , final |
| category | [ModuleCategory](/client/api/feature/module/ModuleCategory.md) | private , final |
| hidden | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |
| notifications | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |
| listening | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |
| settings | `List`<[Setting](/core/setting/Setting.md)<`?`>> | private , final |
| logger | [ILogger](/core/logging/ILogger.md) | protected , final |


## Methods

### getName()

```java
public String getName()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getDescription()

```java
public String getDescription()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getCategory()

```java
public ModuleCategory getCategory()
```

**Returns:** [ModuleCategory](/client/api/feature/module/ModuleCategory.md)

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

**Returns:** `List`<[Setting](/core/setting/Setting.md)<`?`>>

### isHidden()

```java
public boolean isHidden()
```

TODO: this should not be the behavior

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### setHidden()

```java
public void setHidden(boolean hidden)
```

### areNotificationsEnabled()

```java
public boolean areNotificationsEnabled()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

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

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### isListening()

```java
public boolean isListening()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### setListening()

```java
public void setListening(boolean state)
```

### getLogger()

```java
public ILogger getLogger()
```

**Returns:** [ILogger](/core/logging/ILogger.md)

### createCommand()

```java
public ModuleCommand createCommand()
```

**Returns:** [ModuleCommand](/client/api/feature/command/ModuleCommand.md)

