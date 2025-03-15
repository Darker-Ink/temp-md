# TextField

**Package:** `org.rusherhack.client.api.utils.objects`

**Source:** `org/rusherhack/client/api/utils/objects/TextField.java`

**Author:** John200410 9/26/2023



## Overview

`TextField` is a class and implements [ITypeable](ITypeable.md).

## Constructor

```java
public TextField()
```

```java
public TextField(Consumer<String> consumer)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| value | `String` | private |
| shiftPressed | `boolean` | private |
| maxLength | `int` | private , final |
| cursorPos | `int` | private |
| highlightPos | `int` | private |
| consumer | `Consumer`<`String`> | private |


## Methods

### getDisplayText()

```java
public String getDisplayText()
```

**Returns:** `String`

### setConsumer()

```java
public void setConsumer(Consumer<String> consumer)
```

### reset()

```java
public void reset()
```

### charTyped()

```java
public boolean charTyped(char character)
```

**Returns:** `boolean`

### keyTyped()

```java
public boolean keyTyped(int keyCode, int scanCode, int modifiers)
```

**Returns:** `boolean`

### insertText()

```java
public void insertText(String textToWrite)
```

### deleteText()

```java
private void deleteText(int count)
```

### deleteWords()

```java
public void deleteWords(int num)
```

### deleteChars()

```java
public void deleteChars(int num)
```

### getHighlighted()

```java
public String getHighlighted()
```

**Returns:** `String`

### getHighlightStartPos()

```java
public int getHighlightStartPos()
```

**Returns:** `int`

### getHighlightEndPos()

```java
public int getHighlightEndPos()
```

**Returns:** `int`

### setHighlightPos()

```java
public void setHighlightPos(int position)
```

### moveCursor()

```java
public void moveCursor(int delta)
```

### getCursorPos()

```java
private int getCursorPos(int delta)
```

**Returns:** `int`

### moveCursorTo()

```java
public void moveCursorTo(int pos)
```

### setCursorPosition()

```java
public void setCursorPosition(int pos)
```

### moveCursorToStart()

```java
public void moveCursorToStart()
```

### moveCursorToEnd()

```java
public void moveCursorToEnd()
```

### onValueChange()

```java
private void onValueChange(String newText)
```

### getCursorPosition()

```java
public int getCursorPosition()
```

**Returns:** `int`

### getWordPosition()

```java
public int getWordPosition(int numWords)
```

**Returns:** `int`

### getWordPosition()

```java
private int getWordPosition(int n, int pos)
```

**Returns:** `int`

### getWordPosition()

```java
private int getWordPosition(int n, int pos, boolean skipWs)
```

**Returns:** `int`

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
