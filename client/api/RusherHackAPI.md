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
| rusherhack | [IRusherHack](/client/api/IRusherHack.md) | private static |


## Methods

### getEventBus()

```java
public static IEventBus getEventBus()
```

**Returns**: The event bus used to subscribe to events



**Returns:** `IEventBus`

### createLogger()

```java
public static ILogger createLogger(String name)
```

Creates a logger with the specified name

**Returns:** [ILogger](/core/logging/ILogger.md)

### getVersion()

```java
public static String getVersion()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getConfigPath()

```java
public static Path getConfigPath()
```

**Returns:** [Path](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/nio/file/Path.html)

### getModuleManager()

```java
public static IFeatureManager<IModule> getModuleManager()
```

**Returns:** [IFeatureManager](/core/feature/IFeatureManager.md)<[IModule](/client/api/feature/module/IModule.md)>

### getCommandManager()

```java
public static ICommandManager getCommandManager()
```

**Returns:** [ICommandManager](/core/command/ICommandManager.md)

### getHudManager()

```java
public static IHudManager getHudManager()
```

**Returns:** [IHudManager](/client/api/system/IHudManager.md)

### getWindowManager()

```java
public static IWindowManager getWindowManager()
```

**Returns:** [IWindowManager](/client/api/system/IWindowManager.md)

### getThemeManager()

```java
public static IThemeManager getThemeManager()
```

**Returns:** [IThemeManager](/client/api/ui/theme/IThemeManager.md)

### getBindManager()

```java
public static IBindManager getBindManager()
```

**Returns:** [IBindManager](/client/api/bind/IBindManager.md)

### getRelationManager()

```java
public static IRelationManager getRelationManager()
```

**Returns:** [IRelationManager](/client/api/system/IRelationManager.md)

### getRotationManager()

```java
public static IRotationManager getRotationManager()
```

**Returns:** [IRotationManager](/client/api/system/IRotationManager.md)

### getNotificationManager()

```java
public static INotificationManager getNotificationManager()
```

**Returns:** [INotificationManager](/client/api/system/INotificationManager.md)

### getChunkProcessor()

```java
public static IChunkProcessor getChunkProcessor()
```

**Returns:** [IChunkProcessor](/client/api/system/IChunkProcessor.md)

### getServerState()

```java
public static IServerState getServerState()
```

**Returns:** [IServerState](/client/api/system/IServerState.md)

### interactions()

```java
public static IInteractions interactions()
```

**Returns:** [IInteractions](/client/api/system/IInteractions.md)

### getRenderer2D()

```java
public static IRenderer2D getRenderer2D()
```

**Returns:** [IRenderer2D](/client/api/render/IRenderer2D.md)

### getRenderer3D()

```java
public static IRenderer3D getRenderer3D()
```

**Returns:** [IRenderer3D](/client/api/render/IRenderer3D.md)

### fonts()

```java
public static Fonts fonts()
```

**Returns:** [Fonts](/client/api/system/Fonts.md)

### colors()

```java
public static Colors colors()
```

**Returns:** [Colors](/client/api/system/Colors.md)

### entities()

```java
public static Entities entities()
```

**Returns:** [Entities](/client/api/system/Entities.md)

### sendNotification()

```java
public static void sendNotification(NotificationType type, String text)
```

### sendNotification()

```java
public static void sendNotification(NotificationType type, String prefix, String text)
```

