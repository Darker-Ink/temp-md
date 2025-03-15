# LivingNotification

**Package:** `org.rusherhack.core.notification.type`

**Source:** `org/rusherhack/core/notification/type/LivingNotification.java`

This is a notification that has a life span. It will be removed from the notification manager after the life span has passed.



This is useful for notifications that are only meant to be displayed for a short period of time.
* **Author:** John200410 1/27/2023



## Overview

`LivingNotification` is a class that extends [Notification](Notification.md) and implements [ITickable](ITickable.md).

## Constructor

```java
public LivingNotification(String text, NotificationType type)
```

```java
public LivingNotification(String text, NotificationType type, int id)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| timer | [Timer](Timer.md) | private , final |
| lifeSpan | `long` | private , final |
| shouldKill | `boolean` | private |


## Methods

### getTimer()

```java
public Timer getTimer()
```

**Returns:** [Timer](Timer.md)

### getLifeSpan()

```java
public long getLifeSpan()
```

**Returns:** `long`

### shouldKillSelf()

```java
public boolean shouldKillSelf()
```

**Returns:** `boolean`

### kill()

```java
public void kill()
```

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
