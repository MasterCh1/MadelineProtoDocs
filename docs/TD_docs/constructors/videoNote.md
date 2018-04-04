---
title: videoNote
description: Describes video note. Video must have equal width and height, cropped to circle and stored in mpeg4 format
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
## Constructor: videoNote  
[Back to constructors index](index.md)



Describes video note. Video must have equal width and height, cropped to circle and stored in mpeg4 format

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|duration|[int](../types/int.md) | Yes|Duration of the video in seconds as defined by sender|
|length|[int](../types/int.md) | Yes|Video width and height as defined by sender|
|thumb|[photoSize](../constructors/photoSize.md) | Yes|Video thumb as defined by sender, nullable|
|video|[file](../constructors/file.md) | Yes|File with the video|



### Type: [VideoNote](../types/VideoNote.md)

