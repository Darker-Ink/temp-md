# IMixinConnection

**Package:** `org.rusherhack.client.api.accessors.client`

**Source:** `org/rusherhack/client/api/accessors/client/IMixinConnection.java`

**Author:** John200410 9/15/2023



## Overview

`IMixinConnection` is a interface.

## Methods

### getChannel()

```java
 Channel getChannel()
```

**Returns:** `Channel`

### invokeDoSendPacket()

```java
 void invokeDoSendPacket(Packet<?> packet, PacketSendListener sendListener, boolean flush)
```

### invokeChannelRead0()

```java
 void invokeChannelRead0(ChannelHandlerContext context, Packet<?> packet)
```

### invokeGenericsFtw()

```java
static void invokeGenericsFtw(Packet<T> packet, PacketListener listener)
```

