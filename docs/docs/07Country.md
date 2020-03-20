---
tags: [country, list, grabutxxi, docsxxi]
---

# Country

Fetching Data from Country List

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
|  **code** | BASE64ENCODE (MEDIUM STRING) |                          Encryption text code for **INPUT**                         | Movies by Country (country.php?**query**=VVNB) |
| **title** | STRING | Title of country |          ❌          |

## INPUT

Send input data to Country List

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

Result after send data to Country List

```json http
{
  "method": "get",
  "url": "https://xx5k25zsyd.herokuapp.com/getCountry.php",
  "headers": {}
}
```
