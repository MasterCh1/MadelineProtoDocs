---
title: channels.getMessages
description: Get channel/supergroup messages
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: channels.getMessages  
[Back to methods index](index.md)


Get channel/supergroup messages

### Parameters:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|channel|[Username, chat ID, Update, Message or InputChannel](../types/InputChannel.md) | Optional|The channel/supergroup|
|id|Array of [Message ID or InputMessage](../types/InputMessage.md) | Yes|The message IDs|


### Return type: [messages\_Messages](../types/messages_Messages.md)

### Can bots use this method: **YES**


### MadelineProto Example:


```
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$messages_Messages = $MadelineProto->channels->getMessages(['channel' => InputChannel, 'id' => [InputMessage, InputMessage], ]);
```

### [PWRTelegram HTTP API](https://pwrtelegram.xyz) example (NOT FOR MadelineProto):

### As a bot:

POST/GET to `https://api.pwrtelegram.xyz/botTOKEN/madeline`

Parameters:

* method - channels.getMessages
* params - `{"channel": InputChannel, "id": [InputMessage], }`



### As a user:

POST/GET to `https://api.pwrtelegram.xyz/userTOKEN/channels.getMessages`

Parameters:

channel - Json encoded InputChannel

id - Json encoded  array of InputMessage




Or, if you're into Lua:

```
messages_Messages = channels.getMessages({channel=InputChannel, id={InputMessage}, })
```

### Errors this method can return:

| Error    | Description   |
|----------|---------------|
|CHANNEL_INVALID|The provided channel is invalid|
|CHANNEL_PRIVATE|You haven't joined this channel/supergroup|
|MESSAGE_IDS_EMPTY|No message ids were provided|


