# IRusherHack

**Package:** `org.rusherhack.client.api`

**Source:** `org/rusherhack/client/api/IRusherHack.java`

**Author:** John200410 2/23/2023



## Overview

`IRusherHack` is a interface.

## Methods

### getEventBus()

```java
 IEventBus getEventBus()
```

**Returns:** `IEventBus`

### getModuleManager()

```java
 IFeatureManager<IModule> getModuleManager()
```

**Returns:** [IFeatureManager](/core/feature/IFeatureManager.md)<[IModule](/client/api/feature/module/IModule.md)>

### getCommandManager()

```java
 ICommandManager getCommandManager()
```

**Returns:** [ICommandManager](/core/command/ICommandManager.md)

### getHudManager()

```java
 IHudManager getHudManager()
```

**Returns:** [IHudManager](/client/api/system/IHudManager.md)

### getWindowManager()

```java
 IWindowManager getWindowManager()
```

**Returns:** [IWindowManager](/client/api/system/IWindowManager.md)

### getThemeManager()

```java
 IThemeManager getThemeManager()
```

**Returns:** [IThemeManager](/client/api/ui/theme/IThemeManager.md)

### getBindManager()

```java
 IBindManager getBindManager()
```

**Returns:** [IBindManager](/client/api/bind/IBindManager.md)

### getRelationManager()

```java
 IRelationManager getRelationManager()
```

**Returns:** [IRelationManager](/client/api/system/IRelationManager.md)

### getRotationManager()

```java
 IRotationManager getRotationManager()
```

**Returns:** [IRotationManager](/client/api/system/IRotationManager.md)

### getNotificationManager()

```java
 INotificationManager getNotificationManager()
```

**Returns:** [INotificationManager](/client/api/system/INotificationManager.md)

### getChunkProcessor()

```java
 IChunkProcessor getChunkProcessor()
```

**Returns:** [IChunkProcessor](/client/api/system/IChunkProcessor.md)

### getServerState()

```java
 IServerState getServerState()
```

**Returns:** [IServerState](/client/api/system/IServerState.md)

### interactions()

```java
 IInteractions interactions()
```

**Returns:** [IInteractions](/client/api/system/IInteractions.md)

### createLogger()

```java
 ILogger createLogger(String name)
```

**Returns:** [ILogger](/core/logging/ILogger.md)

### getVersion()

```java
 String getVersion()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getConfigPath()

```java
 Path getConfigPath()
```

**Returns:** `Path`

### getRenderer2D()

```java
 IRenderer2D getRenderer2D()
```

**Returns:** [IRenderer2D](/client/api/render/IRenderer2D.md)

### getRenderer3D()

```java
 IRenderer3D getRenderer3D()
```

**Returns:** [IRenderer3D](/client/api/render/IRenderer3D.md)

### fonts()

```java
 Fonts fonts()
```

**Returns:** [Fonts](/client/api/system/Fonts.md)

### colors()

```java
 Colors colors()
```

**Returns:** [Colors](/client/api/system/Colors.md)

### entities()

```java
 Entities entities()
```

**Returns:** [Entities](/client/api/system/Entities.md)

