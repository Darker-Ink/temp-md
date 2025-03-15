# INotificationManager

**Package:** `org.rusherhack.client.api.system`

**Source:** `org/rusherhack/client/api/system/INotificationManager.java`

Interface for sending notifications to the client
* **Author:** John200410



## Overview

`INotificationManager` is a interface that extends [ILog](ILog.md).

## Methods

### shouldNotifyModuleToggles()

```java
 boolean shouldNotifyModuleToggles()
```

**Returns**: true if module toggle notifications are enabled



**Returns:** `boolean`

### send()

```java
default void send(NotificationType type, String text)
```

### send()

```java
default void send(NotificationType type, Component text)
```

### send()

```java
default void send(NotificationType type, String prefix, String text)
```

### send()

```java
default void send(NotificationType type, String prefix, Component text)
```

### send()

```java
default void send(NotificationType type, String text, int id)
```

### send()

```java
default void send(NotificationType type, Component text, int id)
```

### send()

```java
default void send(NotificationType type, String prefix, String text, int id)
```

### send()

```java
 void send(NotificationType type, String prefix, Component text, int id)
```

### chat()

```java
default void chat(String string)
```

### chat()

```java
default void chat(String string, Style textStyle)
```

### chat()

```java
default void chat(Component component)
```

### chat()

```java
 void chat(Component component, int tagColor, Style prefixStyle, int id)
```

### info()

```java
default void info(String message)
```

### warn()

```java
default void warn(String message)
```

### error()

```java
default void error(String message)
```

### debug()

```java
default void debug(String message)
```

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
