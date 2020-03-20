---
tags: [genre, list, grabutxxi, docsxxi]
---

# Genre

Fetching Data from Genre List

<!-- theme: info -->

> ##### **Method**
>
> GET

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
|  **code** | BASE64ENCODE (MEDIUM STRING) |                          Encryption text code for **INPUT**                         | Movies by Genre (genre.php?**query**=QWN0aW9u) |
| **title** | STRING | Title of genre |          ❌          |

## INPUT

Send input data to Genre List

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

Result after send data to Genre List

```json http
{
  "method": "get",
  "url": "https://xx5k25zsyd.herokuapp.com/getGenre.php",
  "headers": {}
}
```
