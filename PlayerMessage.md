# PlayerMessage

**Package:** `org.rusherhack.client.api.utils.objects`

**Source:** `org/rusherhack/client/api/utils/objects/PlayerMessage.java`

Object representing a player chat message
* **Author:** john@rusherhack.org 1/1/2025



## Overview

`PlayerMessage` is a class.

## Constructor

```java
public PlayerMessage(String sender, String message)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| sender | `String` | private , final |
| message | `String` | private , final |


## Methods

### getSender()

```java
public String getSender()
```

**Returns:** `String`

### getMessage()

```java
public String getMessage()
```

**Returns:** `String`

### parse()

```java
public , static PlayerMessage parse(String message, boolean strict)
```

Parses a message from chat
* **Parameter `message`**: the chat message


**Parameter `strict`**: only match vanilla formatting for sender name


**Returns**: parsed player message



**Returns:** [PlayerMessage](PlayerMessage.md)

---

Copyright (c) 2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
