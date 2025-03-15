# IMixinChatComponent

**Package:** `org.rusherhack.client.api.accessors.gui`

**Source:** `org/rusherhack/client/api/accessors/gui/IMixinChatComponent.java`

**Author:** John200410 7/25/2023



## Overview

`IMixinChatComponent` is a interface.

## Methods

### getTrimmedMessages()

```java
 List<GuiMessage.Line> getTrimmedMessages()
```

**Returns:** `List`<`GuiMessage.Line`>

### getAllMessages()

```java
 List<GuiMessage> getAllMessages()
```

**Returns:** `List`<`GuiMessage`>

### getChatScrollbarPos()

```java
 int getChatScrollbarPos()
```

**Returns:** `int`

### getNewMessageSinceScroll()

```java
 boolean getNewMessageSinceScroll()
```

**Returns:** `boolean`

### invokeGetMessageLineIndexAt()

```java
 int invokeGetMessageLineIndexAt(double mouseX, double mouseY)
```

**Returns:** `int`

### invokeGetMessageEndIndexAt()

```java
 int invokeGetMessageEndIndexAt(double mouseX, double mouseY)
```

**Returns:** `int`

### invokeDrawTagIcon()

```java
 void invokeDrawTagIcon(GuiGraphics graphics, int left, int bottom, GuiMessageTag.Icon tagIcon)
```

### invokeScreenToChatX()

```java
 double invokeScreenToChatX(double x)
```

**Returns:** `double`

### invokeScreenToChatY()

```java
 double invokeScreenToChatY(double y)
```

**Returns:** `double`

### invokeRefreshTrimmedMessage()

```java
 void invokeRefreshTrimmedMessage()
```

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
