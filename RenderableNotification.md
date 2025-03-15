# RenderableNotification

**Package:** `org.rusherhack.client.api.ui.notification`

**Source:** `org/rusherhack/client/api/ui/notification/RenderableNotification.java`

**Author:** John200410 1/27/2023



## Overview

`RenderableNotification` is a class that extends [LivingNotification](LivingNotification.md) and implements [IRenderable2D](IRenderable2D.md), [IClickable](IClickable.md).

## Constructor

```java
public RenderableNotification(String text, NotificationType type)
```

```java
public RenderableNotification(String text, NotificationType type, int id)
```

```java
public RenderableNotification(Component component, NotificationType type)
```

```java
public RenderableNotification(Component component, NotificationType type, int id)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| component | `Component` | private , final |


## Methods

### getComponent()

```java
public Component getComponent()
```

**Returns:** `Component`

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
