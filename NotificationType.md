# NotificationType

**Package:** `org.rusherhack.core.notification`

**Source:** `org/rusherhack/core/notification/NotificationType.java`

**Author:** John200410 1/27/2023



## Overview

`NotificationType` is a enum.

## Constructor

```java
 NotificationType(int typeID, long lifeSpan)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| typeID | `int` | private , final |
| lifeSpan | `long` | private , final |


## Constants

### INFO

Arguments: 1, 5000L

### WARNING

Arguments: 2, 7500L

### ERROR

Arguments: 3, 10000L

### HINT

Arguments: 4, 5000L

### DEBUG

Arguments: 256, 5000L

## Methods

### getTypeID()

```java
public int getTypeID()
```

**Returns:** `int`

### getLifeSpan()

```java
public long getLifeSpan()
```

**Returns:** `long`

### fromTypeID()

```java
public , static NotificationType fromTypeID(int typeID)
```

**Returns:** [NotificationType](NotificationType.md)

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
