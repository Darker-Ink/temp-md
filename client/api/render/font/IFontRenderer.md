# IFontRenderer

**Package:** `org.rusherhack.client.api.render.font`

**Source:** `org/rusherhack/client/api/render/font/IFontRenderer.java`

Interface for font rendering



TODO: documentation
* **Author:** John200410



## Overview

`IFontRenderer` is a interface that extends [IRenderer](/client/api/render/IRenderer.md), [IScissorable](/client/api/render/IScissorable.md).

## Methods

### drawString()

```java
default double drawString(String text, double x, double y, int color)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawString()

```java
default double drawString(FormattedText text, double x, double y, int color)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawString()

```java
default double drawString(FormattedCharSequence text, double x, double y, int color)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawString()

```java
default double drawString(String text, double x, double y, int color, boolean shadow)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawString()

```java
default double drawString(FormattedText text, double x, double y, int color, boolean shadow)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawString()

```java
default double drawString(FormattedCharSequence text, double x, double y, int color, boolean shadow)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawString()

```java
 double drawString(PoseStack matrixStack, String text, double x, double y, int color, boolean shadow)
```

Draws a string at the specified coordinates
* **Parameter `matrixStack`**: the matrix stack to use if the font renderer is not currently building


**Parameter `text`**: string to draw


**Parameter `x`**: x coordinate


**Parameter `y`**: y coordinate


**Parameter `color`**: argb color of the string


**Parameter `shadow`**: whether to draw a shadow


**Returns**: the end x coordinate of the drawn string



**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawString()

```java
 double drawString(PoseStack matrixStack, FormattedCharSequence text, double x, double y, int color, boolean shadow)
```

Draws a string at the specified coordinates
* **Parameter `matrixStack`**: the matrix stack to use if the font renderer is not currently building


**Parameter `text`**: text component to draw


**Parameter `x`**: x coordinate


**Parameter `y`**: y coordinate


**Parameter `color`**: argb color of the string


**Parameter `shadow`**: whether to draw a shadow


**Returns**: the end x coordinate of the drawn string



**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawText()

```java
default double drawText(String text, double x, double y, int color, double maxWidth, double spacing)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawText()

```java
default double drawText(String text, double x, double y, int color, boolean shadow, double maxWidth, double spacing)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawText()

```java
default double drawText(FormattedText text, double x, double y, int color, double maxWidth, double spacing)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawText()

```java
default double drawText(FormattedText text, double x, double y, int color, boolean shadow, double maxWidth, double spacing)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawText()

```java
 double drawText(PoseStack matrixStack, String text, double x, double y, int color, boolean shadow, double maxWidth, double spacing)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### drawText()

```java
 double drawText(PoseStack matrixStack, FormattedText text, double x, double y, int color, boolean shadow, double maxWidth, double spacing)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getStringWidth()

```java
 double getStringWidth(String text)
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getFontHeight()

```java
 double getFontHeight()
```

**Returns:** [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html)

### getDefaultShadowState()

```java
 boolean getDefaultShadowState()
```

If the shadow parameter is not specified, font renderer will use this value
* **Returns**: the default shadow state



**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### setDefaultShadowState()

```java
 void setDefaultShadowState(boolean state)
```

Sets the default shadow state to be used whenever the shadow parameter is not specified
* @param state

### splitString()

```java
default List<String> splitString(String string, double maxWidth)
```

**Returns:** [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<[String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)>

### trimStringToWidth()

```java
default String trimStringToWidth(String string, double width)
```

**Returns:** [String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)

