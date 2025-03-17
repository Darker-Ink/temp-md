# SimpleView

**Package:** `org.rusherhack.client.api.ui.window.view`

**Source:** `org/rusherhack/client/api/ui/window/view/SimpleView.java`

## Overview

`SimpleView` is a class that extends [WindowView](/client/api/ui/window/view/WindowView.md).

## Constructor

```java
public SimpleView(Window window, List<? extends WindowContent> contentList)
```

```java
public SimpleView(String name, Window window, List<? extends WindowContent> contentList)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| alignment | [Alignment](/client/api/feature/hud/Alignment.md) | protected |
| topPadding | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | protected |
| leftPadding | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | protected |
| contentPadding | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | protected |
| viewWidthModifier | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private |


## Methods

### renderViewContent()

```java
public void renderViewContent(double mouseX, double mouseY)
```

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

### getTopOffset()

```java
protected double getTopOffset()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getLeftOffset()

```java
protected double getLeftOffset()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### setTopPadding()

```java
public void setTopPadding(double topPadding)
```

### setLeftPadding()

```java
public void setLeftPadding(double leftPadding)
```

### setContentPadding()

```java
public void setContentPadding(double contentPadding)
```

### setViewWidthModifier()

```java
public void setViewWidthModifier(double viewWidthModifier)
```

### setAlignment()

```java
public void setAlignment(Alignment alignment)
```

