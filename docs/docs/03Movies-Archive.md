---
tags: [movies, archive, grabutxxi, docsxxi]
---

# Movies Archive

Fetching Data from Movies Archive

<!-- theme: danger -->

> ##### **Method**
>
> NONE

<!-- theme: info -->

> ##### **Emoji Tags**
>
> **🗝 = KEY**
>
> **✏ = VALUE**
>
> **📝 = DESCRIPTION**

|     🗝    |               ✏              |                                          📝                                         |        INPUT        |
| :-------: | :--------------------------: | :---------------------------------------------------------------------------------: | :-----------------: |
|  **code** | BASE64ENCODE (MEDIUM STRING) |                          Encryption text code for **INPUT**                         | Playlist (playlist.php?**query**=ZXhvcmNpc20tbW92aWVzLXBsYXlsaXN0) |
| **image** | BASE64ENCODE (LONG STRING) | Image poster of archive (contains long character, maybe make ur loading is to bad) ⚠ |          ❌          |

## INPUT

Send input data to Movies Archive

<!-- theme: info -->

> ##### **Emoji Tags**
>
> **🗝 = KEY**
>
> **✏ = VALUE**
>
> **✍ = EXAMPLE**

|  🗝 |  ✏  |                           ✍                          | REQUIRED | OPTIONAL |
| :-: | :-: | :--------------------------------------------------: | :------: | :------: |
|  ❌  |  ❌  | ❌ |     ❌    |     ❌    |

## OUTPUT

Result after send data to Movies Archive

```json http
{
  "method": "get",
  "url": "https://xx5k25zsyd.herokuapp.com/archive.php",
  "headers": {}
}
```
