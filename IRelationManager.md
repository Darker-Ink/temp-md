# IRelationManager

**Package:** `org.rusherhack.client.api.system`

**Source:** `org/rusherhack/client/api/system/IRelationManager.java`

**Author:** John200410 6/21/2023



## Overview

`IRelationManager` is a interface.

## Methods

### isFriend()

```java
 boolean isFriend(String username)
```

**Returns:** `boolean`

### isFriend()

```java
default boolean isFriend(Entity entity)
```

**Returns:** `boolean`

### isEnemy()

```java
 boolean isEnemy(String username)
```

**Returns:** `boolean`

### isEnemy()

```java
default boolean isEnemy(Entity entity)
```

**Returns:** `boolean`

### addFriend()

```java
 void addFriend(String username)
```

### addFriend()

```java
default void addFriend(Entity entity)
```

### addEnemy()

```java
 void addEnemy(String username)
```

### addEnemy()

```java
default void addEnemy(Entity entity)
```

### removeFriend()

```java
 void removeFriend(String username)
```

### removeFriend()

```java
default void removeFriend(Entity entity)
```

### removeEnemy()

```java
 void removeEnemy(String username)
```

### removeEnemy()

```java
default void removeEnemy(Entity entity)
```

### getFriends()

```java
 List<PlayerRelation> getFriends()
```

**Returns:** `List`<[PlayerRelation](PlayerRelation.md)>

### getEnemies()

```java
 List<PlayerRelation> getEnemies()
```

**Returns:** `List`<[PlayerRelation](PlayerRelation.md)>

---

Copyright (c) 2023-2024 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
