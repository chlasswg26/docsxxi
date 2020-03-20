---
tags: [popular, movies, grabutxxi, docsxxi]
---

# Popular Movies

Fetching Data from Popular Movies

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
|  **code** | BASE64ENCODE (MEDIUM STRING) |                          Encryption text code for **INPUT**                         | Post (post.php?**query**=c2hlcGFyZC0yMDIw) |
| **title** |            STRING            |                                   Title of movies                                   |          ❌          |
| **image** | BASE64ENCODE (LONG STRING) | Image poster of movies (contains long character, maybe make ur loading is to bad) ⚠ |          ❌          |

## INPUT

Send input data to Popular Movies

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

Result after send data to Popular Movies

```json http
{
  "method": "get",
  "url": "https://xx5k25zsyd.herokuapp.com/popular.php",
  "headers": {}
}
```
