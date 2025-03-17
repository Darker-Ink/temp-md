# EventInteract

**Package:** `org.rusherhack.client.api.events.player`

**Source:** `org/rusherhack/client/api/events/player/EventInteract.java`


@author historian**Author:** John200410 7/5/2023



## Overview

`EventInteract` is a class that extends `EventCancellable`.

## Constructor

```java
public EventInteract(Entity entity, InteractionHand hand, boolean usingSecondaryAction, Action action, EntityHitResult hitResult)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| targetEntity | `Entity` | private , final |
| hand | `InteractionHand` | private , final |
| action | [Action](/client/api/events/player/Action.md) | private , final |
| hitResult | `EntityHitResult` | private , final |
| usingSecondaryAction | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private |


## Methods

### getTargetEntity()

```java
public Entity getTargetEntity()
```

**Returns:** `Entity`

### getHand()

```java
public InteractionHand getHand()
```

**Returns:** `InteractionHand`

### getAction()

```java
public Action getAction()
```

**Returns:** [Action](/client/api/events/player/Action.md)

### getHitResult()

```java
public EntityHitResult getHitResult()
```

**Returns:** `EntityHitResult`

### isUsingSecondaryAction()

```java
public boolean isUsingSecondaryAction()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### setUsingSecondaryAction()

```java
public void setUsingSecondaryAction(boolean usingSecondaryAction)
```

### getPreferredStage()

```java
public Stage getPreferredStage()
```

**Returns:** `Stage`

