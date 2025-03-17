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

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### getNewMessageSinceScroll()

```java
 boolean getNewMessageSinceScroll()
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### invokeGetMessageLineIndexAt()

```java
 int invokeGetMessageLineIndexAt(double mouseX, double mouseY)
```

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### invokeGetMessageEndIndexAt()

```java
 int invokeGetMessageEndIndexAt(double mouseX, double mouseY)
```

**Returns:** [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html)

### invokeDrawTagIcon()

```java
 void invokeDrawTagIcon(GuiGraphics graphics, int left, int bottom, GuiMessageTag.Icon tagIcon)
```

### invokeScreenToChatX()

```java
 double invokeScreenToChatX(double x)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### invokeScreenToChatY()

```java
 double invokeScreenToChatY(double y)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### invokeRefreshTrimmedMessage()

```java
 void invokeRefreshTrimmedMessage()
```

