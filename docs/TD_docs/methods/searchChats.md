---
title: searchChats
description: Searches for specified query in the title and username of known chats, offline request. Returns chats in the order of them in the chat list
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: searchChats  
[Back to methods index](index.md)


YOU CANNOT USE THIS METHOD IN MADELINEPROTO


Searches for specified query in the title and username of known chats, offline request. Returns chats in the order of them in the chat list

### Parameters:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|query|[string](../types/string.md) | Yes|Query to search for, if query is empty, returns up to 20 recently found chats|
|limit|[int](../types/int.md) | Yes|Maximum number of chats to be returned|


### Return type: [Chats](../types/Chats.md)

