# Version

**Package:** `org.rusherhack.core.utils`

**Source:** `org/rusherhack/core/utils/Version.java`

**Author:** John200410 6/2/2024



## Overview

`Version` is a class and implements `Comparable`.

## Constructor

```java
public Version(int major, int minor, int patch)
```

## Fields

| Name | Type | Modifiers |
|------|------|----------|
| major | `int` | private , final |
| minor | `int` | private , final |
| patch | `int` | private , final |


## Methods

### getMajor()

```java
public int getMajor()
```

**Returns:** `int`

### getMinor()

```java
public int getMinor()
```

**Returns:** `int`

### getPatch()

```java
public int getPatch()
```

**Returns:** `int`

### getString()

```java
public String getString(boolean includeNullPatch)
```

**Returns:** `String`

### toString()

```java
public String toString()
```

**Returns:** `String`

### equals()

```java
public boolean equals(Object obj)
```

**Returns:** `boolean`

### hashCode()

```java
public int hashCode()
```

**Returns:** `int`

### fromString()

```java
public , static Version fromString(String version)
```

**Returns:** [Version](Version.md)

### compareTo()

```java
public int compareTo(Version other)
```

**Returns:** `int`

---

Copyright (c) 2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
