# RusherHackAPI

**Package:** `org.rusherhack.client.api`

**Source:** `org/rusherhack/client/api/RusherHackAPI.java`

RusherHack public API accessor
TODO: javadocs
* **Author:** John200410 12/29/2022



## Overview

`RusherHackAPI` is a class.

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| rusherhack | [IRusherHack](IRusherHack.md) | private , static |


## Methods

### getEventBus()

```java
public , static IEventBus getEventBus()
```

**Returns**: The event bus used to subscribe to events



**Returns:** `IEventBus`

### createLogger()

```java
public , static ILogger createLogger(String name)
```

Creates a logger with the specified name

**Returns:** [ILogger](ILogger.md)

### getVersion()

```java
public , static String getVersion()
```

**Returns:** `String`

### getConfigPath()

```java
public , static Path getConfigPath()
```

**Returns:** `Path`

### getModuleManager()

```java
public , static IFeatureManager<IModule> getModuleManager()
```

**Returns:** [IFeatureManager](IFeatureManager.md)<[IModule](IModule.md)>

### getCommandManager()

```java
public , static ICommandManager getCommandManager()
```

**Returns:** [ICommandManager](ICommandManager.md)

### getHudManager()

```java
public , static IHudManager getHudManager()
```

**Returns:** [IHudManager](IHudManager.md)

### getWindowManager()

```java
public , static IWindowManager getWindowManager()
```

**Returns:** [IWindowManager](IWindowManager.md)

### getThemeManager()

```java
public , static IThemeManager getThemeManager()
```

**Returns:** [IThemeManager](IThemeManager.md)

### getBindManager()

```java
public , static IBindManager getBindManager()
```

**Returns:** [IBindManager](IBindManager.md)

### getRelationManager()

```java
public , static IRelationManager getRelationManager()
```

**Returns:** [IRelationManager](IRelationManager.md)

### getRotationManager()

```java
public , static IRotationManager getRotationManager()
```

**Returns:** [IRotationManager](IRotationManager.md)

### getNotificationManager()

```java
public , static INotificationManager getNotificationManager()
```

**Returns:** [INotificationManager](INotificationManager.md)

### getChunkProcessor()

```java
public , static IChunkProcessor getChunkProcessor()
```

**Returns:** [IChunkProcessor](IChunkProcessor.md)

### getServerState()

```java
public , static IServerState getServerState()
```

**Returns:** [IServerState](IServerState.md)

### interactions()

```java
public , static IInteractions interactions()
```

**Returns:** [IInteractions](IInteractions.md)

### getRenderer2D()

```java
public , static IRenderer2D getRenderer2D()
```

**Returns:** [IRenderer2D](IRenderer2D.md)

### getRenderer3D()

```java
public , static IRenderer3D getRenderer3D()
```

**Returns:** [IRenderer3D](IRenderer3D.md)

### fonts()

```java
public , static Fonts fonts()
```

**Returns:** [Fonts](Fonts.md)

### colors()

```java
public , static Colors colors()
```

**Returns:** [Colors](Colors.md)

### entities()

```java
public , static Entities entities()
```

**Returns:** [Entities](Entities.md)

### sendNotification()

```java
public , static void sendNotification(NotificationType type, String text)
```

### sendNotification()

```java
public , static void sendNotification(NotificationType type, String prefix, String text)
```

---

Copyright (c) 2022-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
