---
title: photo
description: photo attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: photo  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|has\_stickers|[Bool](../types/Bool.md) | Optional|
|id|[long](../types/long.md) | Yes|
|access\_hash|[long](../types/long.md) | Yes|
|date|[int](../types/int.md) | Yes|
|sizes|Array of [PhotoSize](../types/PhotoSize.md) | Yes|



### Type: [Photo](../types/Photo.md)


### Example:

```
$photo = ['_' => 'photo', 'has_stickers' => Bool, 'id' => long, 'access_hash' => long, 'date' => int, 'sizes' => [PhotoSize, PhotoSize]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "photo", "has_stickers": Bool, "id": long, "access_hash": long, "date": int, "sizes": [PhotoSize]}
```


Or, if you're into Lua:  


```
photo={_='photo', has_stickers=Bool, id=long, access_hash=long, date=int, sizes={PhotoSize}}

```


