---
title: sendBotStartMessage
description: Invites bot to a chat (if it is not in the chat) and send /start to it. Bot can't be invited to a private chat other than chat with the bot. Bots can't be invited to broadcast channel chats and secret chats. Returns sent message
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: sendBotStartMessage  
[Back to methods index](index.md)


YOU CANNOT USE THIS METHOD IN MADELINEPROTO


Invites bot to a chat (if it is not in the chat) and send /start to it. Bot can't be invited to a private chat other than chat with the bot. Bots can't be invited to broadcast channel chats and secret chats. Returns sent message

### Parameters:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|bot\_user\_id|[int](../types/int.md) | Yes|Identifier of the bot|
|chat\_id|[int53](../types/int53.md) | Yes|Identifier of the chat|
|parameter|[string](../types/string.md) | Yes|Hidden parameter sent to bot for deep linking (https: api.telegram.org/bots#deep-linking)|


### Return type: [Message](../types/Message.md)

