---
title: channelAdminLogEventActionEditMessage
description: channelAdminLogEventActionEditMessage attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: channelAdminLogEventActionEditMessage  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|prev\_message|[Message](../types/Message.md) | Optional|
|new\_message|[Message](../types/Message.md) | Optional|



### Type: [ChannelAdminLogEventAction](../types/ChannelAdminLogEventAction.md)


### Example:

```
$channelAdminLogEventActionEditMessage = ['_' => 'channelAdminLogEventActionEditMessage', 'prev_message' => Message, 'new_message' => Message];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "channelAdminLogEventActionEditMessage", "prev_message": Message, "new_message": Message}
```


Or, if you're into Lua:  


```
channelAdminLogEventActionEditMessage={_='channelAdminLogEventActionEditMessage', prev_message=Message, new_message=Message}

```


