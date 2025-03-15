# IMixinMinecraft

**Package:** `org.rusherhack.client.api.accessors.client`

**Source:** `org/rusherhack/client/api/accessors/client/IMixinMinecraft.java`

**Author:** John200410 5/30/2023



## Overview

`IMixinMinecraft` is a interface.

## Methods

### getTimer()

```java
 DeltaTracker.Timer getTimer()
```

**Returns:** `DeltaTracker.Timer`

### getRightClickDelay()

```java
 int getRightClickDelay()
```

**Returns:** `int`

### setRightClickDelay()

```java
 void setRightClickDelay(int rightClickDelay)
```

### invokeStartUseItem()

```java
 void invokeStartUseItem()
```

### setUser()

```java
 void setUser(User user)
```

### setPlayerSocialManager()

```java
 void setPlayerSocialManager(PlayerSocialManager playerSocialManager)
```

### setProfileKeyPairManager()

```java
 void setProfileKeyPairManager(ProfileKeyPairManager profileKeyPairManager)
```

### setReportingContext()

```java
 void setReportingContext(ReportingContext reportingContext)
```

### setUserApiService()

```java
 void setUserApiService(UserApiService userApiService)
```

### invokeCreateUserApiService()

```java
 UserApiService invokeCreateUserApiService(YggdrasilAuthenticationService yggdrasilAuthenticationService, GameConfig gameConfig)
```

**Returns:** `UserApiService`

### getAuthenticationService()

```java
 YggdrasilAuthenticationService getAuthenticationService()
```

**Returns:** `YggdrasilAuthenticationService`

---

Copyright (c) 2023-2025 Rusher Development LLC. All Rights Reserved.
* Unauthorized copying of this file, via any medium is strictly prohibited, proprietary, and confidential.
