# HudHandlerBase

**Package:** `org.rusherhack.client.api.ui.hud`

**Source:** `org/rusherhack/client/api/ui/hud/HudHandlerBase.java`

Handler for hud elements
* **Author:** John200410 3/26/2024



## Overview

`HudHandlerBase` is a class that extends [ElementHandlerBase](/client/api/ui/ElementHandlerBase.md).

## Constructor

```java
public HudHandlerBase(boolean scaledWithMinecraftGui)
```

**Parameter `scaledWithMinecraftGui`**: sets whether elements should be scaled with the minecraft gui



## Fields

| Name | Type | Modifiers |
|------|------|----------|
| lastFontRenderer | [IFontRenderer](/client/api/render/font/IFontRenderer.md) | private |


## Methods

### getElements()

```java
public List<HudElement> getElements()
```

**Returns:** [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<[HudElement](/client/api/feature/hud/HudElement.md)>

### moveElementToTop()

```java
public void moveElementToTop(HudElement element)
```

### render()

```java
public void render(RenderContext context, double mouseX, double mouseY)
```

### initialize()

```java
public void initialize()
```

### setDefaultPositions()

```java
public void setDefaultPositions()
```

### tick()

```java
public void tick()
```

### mouseClicked()

```java
public boolean mouseClicked(double mouseX, double mouseY, int button)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### consumeElementMouseClick()

```java
protected boolean consumeElementMouseClick(HudElement element, double mouseX, double mouseY, int button)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### mouseReleased()

```java
public void mouseReleased(double mouseX, double mouseY, int button)
```

### mouseMoved()

```java
public void mouseMoved(double mouseX, double mouseY)
```

### mouseScrolled()

```java
public boolean mouseScrolled(double mouseX, double mouseY, double delta)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

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

### renderElements()

```java
public void renderElements(RenderContext renderContext, double mouseX, double mouseY)
```

### renderHudElement()

```java
public void renderHudElement(HudElement hudElement, RenderContext renderContext, double mouseX, double mouseY)
```

### renderPrimitiveHudElement()

```java
protected void renderPrimitiveHudElement(HudElement hudElement, RenderContext renderContext, double mouseX, double mouseY)
```

### getBackgroundColor()

```java
protected Color getBackgroundColor(HudElement hudElement, double mouseX, double mouseY)
```

**Returns:** `Color`

### renderHudElementBackground()

```java
protected void renderHudElementBackground(HudElement hudElement, RenderContext renderContext, IRenderer2D renderer, double width, double height, int color)
```

Renders the background of a hud element

### getHudManagerPanel()

```java
public PanelHandlerBase<?> getHudManagerPanel()
```

**Returns:** [PanelHandlerBase](/client/api/ui/panel/PanelHandlerBase.md)<`?`>

### isElementHovered()

```java
public boolean isElementHovered(HudElement element, double mouseX, double mouseY)
```

**Returns:** [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html)

### getFontRenderer()

```java
public IFontRenderer getFontRenderer()
```

**Returns:** [IFontRenderer](/client/api/render/font/IFontRenderer.md)

