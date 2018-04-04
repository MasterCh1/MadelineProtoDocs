---
title: msgs_ack
description: msgs_ack attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
## Constructor: msgs\_ack  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|msg\_ids|Array of [long](../types/long.md) | Yes|



### Type: [MsgsAck](../types/MsgsAck.md)


### Example:

```
$msgs_ack = ['_' => 'msgs_ack', 'msg_ids' => [long, long]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "msgs_ack", "msg_ids": [long]}
```


Or, if you're into Lua:  


```
msgs_ack={_='msgs_ack', msg_ids={long}}

```

