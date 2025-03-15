# FeatureCommand

**Package:** `org.rusherhack.client.api.feature.command`

**Source:** `org/rusherhack/client/api/feature/command/FeatureCommand.java`

A command that lets you configure a feature's settings.
* **Author:** John200410 8/11/2023



## Overview

`FeatureCommand` is a class that extends [Command](Command.md).

## Constructor

```java
public FeatureCommand(IFeatureConfigurable feature)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| feature | [IFeatureConfigurable](IFeatureConfigurable.md) | private , final |


## Methods

### changeSetting()

```java
private String changeSetting(Setting<?> setting, Optional<SettingValue> value)
```

**Returns:** `String`

### isHidden()

```java
public boolean isHidden()
```

**Returns:** `boolean`

### getFeature()

```java
public IFeatureConfigurable getFeature()
```

**Returns:** [IFeatureConfigurable](IFeatureConfigurable.md)

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
