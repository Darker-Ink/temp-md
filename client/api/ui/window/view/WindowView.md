# WindowView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/WindowView.java`

A WindowView is a WindowContent that is able to render a set of other WindowContents in a defined way.



WindowViews should also be sure to set the position of the WindowContent before rendering it so that it is aware of its position.
* **Author:** John200410



## Overview

`WindowView` is a class that extends [WindowContent](/client/api/ui/window/content/WindowContent.md) and implements [INamed](/core/interfaces/INamed.md).

## Constructor

```java
public WindowView(Window window, List<? extends WindowContent> contentList)
```

```java
public WindowView(String name, Window window, List<? extends WindowContent> contentList)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| viewWidth | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private |
| viewHeight | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private |
| contentList | `List`<`? extends WindowContent`> | protected |
| viewName | [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html) | private |


## Methods

### renderViewContent()

```java
public abstract void renderViewContent(double mouseX, double mouseY)
```

### renderContent()

```java
public void renderContent(double mouseX, double mouseY, WindowView parent)
```

### unfocus()

```java
public void unfocus()
```

### mouseClicked()

```java
public boolean mouseClicked(double mouseX, double mouseY, int button)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### mouseReleased()

```java
public void mouseReleased(double mouseX, double mouseY, int button)
```

### charTyped()

```java
public boolean charTyped(char character)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### keyTyped()

```java
public boolean keyTyped(int key, int scanCode, int modifiers)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### mouseScrolled()

```java
public boolean mouseScrolled(double mouseX, double mouseY, double delta)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### tick()

```java
public void tick()
```

### setViewWidth()

```java
public void setViewWidth(double viewWidth)
```

### setViewHeight()

```java
public void setViewHeight(double viewHeight)
```

### getWidth()

```java
public double getWidth()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getHeight()

```java
public double getHeight()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getViewWidth()

```java
public double getViewWidth()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getViewHeight()

```java
public double getViewHeight()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getName()

```java
public String getName()
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

### getContent()

```java
public List<WindowContent> getContent()
```

**Returns:** `List`<[WindowContent](/client/api/ui/window/content/WindowContent.md)>

### setContentList()

```java
public void setContentList(List<? extends WindowContent> contentList)
```

### getHandler()

```java
protected WindowHandlerBase getHandler()
```

**Returns:** [WindowHandlerBase](/client/api/ui/window/WindowHandlerBase.md)

### getViewHandler()

```java
protected WindowViewHandlerBase getViewHandler()
```

**Returns:** [WindowViewHandlerBase](/client/api/ui/window/WindowViewHandlerBase.md)

