---
title: documentAttributeVideo
description: documentAttributeVideo attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: documentAttributeVideo  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|duration|[int](../types/int.md) | Optional|
|w|[int](../types/int.md) | Optional|
|h|[int](../types/int.md) | Optional|



### Type: [DocumentAttribute](../types/DocumentAttribute.md)


### Example:

```
$documentAttributeVideo = ['_' => 'documentAttributeVideo', 'duration' => int, 'w' => int, 'h' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "documentAttributeVideo", "duration": int, "w": int, "h": int}
```


Or, if you're into Lua:  


```
documentAttributeVideo={_='documentAttributeVideo', duration=int, w=int, h=int}

```


