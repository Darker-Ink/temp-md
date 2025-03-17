# ListHudElement

**Package:** `org.rusherhack.client.api.feature.hud`

**Source:** `org/rusherhack/client/api/feature/hud/ListHudElement.java`

A hud element that will display a list of items
* **Author:** John200410 6/9/2023



## Overview

`ListHudElement` is a class that extends [HudElement](/client/api/feature/hud/HudElement.md).

## Constructor

```java
public ListHudElement(String name)
```

```java
public ListHudElement(String name, boolean sorting)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| width | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private |
| height | [double](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Double.html) | private |
| cache | [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<[String](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/String.html)> | private |
| members | [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<[ListItem](/client/api/feature/hud/ListItem.md)> | private |
| sorting | [boolean](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Boolean.html) | private final |
| max | [int](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/lang/Integer.html) | private |
| color | [ColorSetting](/client/api/setting/ColorSetting.md) | protected final |
| colorMode | [EnumSetting](/core/setting/EnumSetting.md)<[ColorMode](/client/api/system/ColorMode.md)> | protected final |
| sortMode | [EnumSetting](/core/setting/EnumSetting.md)<[SortingMode](/client/api/feature/hud/SortingMode.md)> | protected final |
| animations | [BooleanSetting](/core/setting/BooleanSetting.md) | protected final |


## Methods

### renderContent()

```java
public void renderContent(RenderContext context, double mouseX, double mouseY)
```

### renderList()

```java
private void renderList(RenderContext renderContext)
```

### tick()

```java
public void tick()
```

### resort()

```java
public void resort()
```

### setMax()

```java
public void setMax(int max)
```

### add()

```java
public void add(ListItem member)
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

### getMembers()

```java
public List<ListItem> getMembers()
```

**Returns:** [List](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/util/List.html)<[ListItem](/client/api/feature/hud/ListItem.md)>

