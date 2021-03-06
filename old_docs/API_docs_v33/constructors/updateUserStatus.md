---
title: updateUserStatus
description: updateUserStatus attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateUserStatus  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|user\_id|[int](../types/int.md) | Yes|
|status|[UserStatus](../types/UserStatus.md) | Optional|



### Type: [Update](../types/Update.md)


### Example:

```
$updateUserStatus = ['_' => 'updateUserStatus', 'user_id' => int, 'status' => UserStatus];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateUserStatus", "user_id": int, "status": UserStatus}
```


Or, if you're into Lua:  


```
updateUserStatus={_='updateUserStatus', user_id=int, status=UserStatus}

```


