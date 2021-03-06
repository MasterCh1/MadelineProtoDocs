---
title: upload.fileCdnRedirect
description: upload_fileCdnRedirect attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: upload.fileCdnRedirect  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|dc\_id|[int](../types/int.md) | Yes|
|file\_token|[bytes](../types/bytes.md) | Yes|
|encryption\_key|[bytes](../types/bytes.md) | Yes|
|encryption\_iv|[bytes](../types/bytes.md) | Yes|
|file\_hashes|Array of [FileHash](../types/FileHash.md) | Yes|



### Type: [upload\_File](../types/upload_File.md)


### Example:

```
$upload_fileCdnRedirect = ['_' => 'upload.fileCdnRedirect', 'dc_id' => int, 'file_token' => 'bytes', 'encryption_key' => 'bytes', 'encryption_iv' => 'bytes', 'file_hashes' => [FileHash, FileHash]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "upload.fileCdnRedirect", "dc_id": int, "file_token": {"_": "bytes", "bytes":"base64 encoded bytes"}, "encryption_key": {"_": "bytes", "bytes":"base64 encoded bytes"}, "encryption_iv": {"_": "bytes", "bytes":"base64 encoded bytes"}, "file_hashes": [FileHash]}
```


Or, if you're into Lua:  


```
upload_fileCdnRedirect={_='upload.fileCdnRedirect', dc_id=int, file_token='bytes', encryption_key='bytes', encryption_iv='bytes', file_hashes={FileHash}}

```


