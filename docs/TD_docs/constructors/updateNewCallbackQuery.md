---
title: updateNewCallbackQuery
description: Bots only. New incoming callback query
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateNewCallbackQuery  
[Back to constructors index](index.md)



Bots only. New incoming callback query

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|id|[int64](../constructors/int64.md) | Yes|Unique query identifier|
|sender\_user\_id|[int](../types/int.md) | Yes|Identifier of the user who sent the query|
|chat\_id|[int53](../types/int53.md) | Yes|Identifier of the chat, in which the query was sent|
|message\_id|[int53](../types/int53.md) | Yes|Identifier of the message, from which the query is originated|
|chat\_instance|[int64](../constructors/int64.md) | Yes|Identifier, uniquely corresponding to the chat a message was sent to|
|payload|[CallbackQueryPayload](../types/CallbackQueryPayload.md) | Yes|Query payload|



### Type: [Update](../types/Update.md)


