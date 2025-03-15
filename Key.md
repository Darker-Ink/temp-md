# Key

**Package:** `org.rusherhack.client.api.events.client.input`

**Source:** `org/rusherhack/client/api/events/client/input/EventMouse.java`

This event is called when a mouse button is pressed or released

## Overview

`Key` is a class that extends [EventMouse](EventMouse.md).

## Constructor

```java
public Key(int button, int action, int modifiers)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| button | `int` | private , final |
| action | `int` | private , final |
| modifiers | `int` | private , final |


## Methods

### getButton()

```java
public int getButton()
```

**Returns:** `int`

### getAction()

```java
public int getAction()
```

**Returns**: {

@link org.lwjgl.glfw.GLFW#GLFW_PRESS}



`org.lwjgl.glfw.GLFW`#GLFW_RELEASE



`org.lwjgl.glfw.GLFW`#GLFW_REPEAT

**Returns:** `int`

### getModifiers()

```java
public int getModifiers()
```

**Returns:** `int`

### getStage()

```java
public Stage getStage()
```

`Stage`#PRE - called before the key is processed



`Stage`#ON - called before the key is pressed, but only while there is no gui screen open

**Returns:** `Stage`

---

Copyright (c) 2023 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
