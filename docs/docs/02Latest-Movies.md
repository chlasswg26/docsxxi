---
tags: [latest, movies, grabutxxi, docsxxi]
---

# Latest Movies

Fetching Data from Latest Movies

<!-- theme: info -->

> ##### **Method**
>
> GET

<!-- theme: info -->

> ##### **Emoji Tags**
>
> **🗝 = KEY**
> 
> **➖ = SUB KEY**
>
> **✏ = VALUE**
>
> **📝 = DESCRIPTION**

|     🗝    |     ➖    |               ✏              |                                          📝                                         |        INPUT        |
| :-------: | :-------: | :--------------------------: | :---------------------------------------------------------------------------------: | :-----------------: |
| **page** |  | ❌ |                          Parent Key for Pagination                         |          ❌          |
|  | **isPaging** |            TRUE / FALSE (BOOLEAN)            |                                   Does it have discrete pages for **INPUT**                                   |          ❌          |
|  | **next** | NUMBER / NULL (INTEGER) | Number to the next page for **INPUT** |          Latest Movies (latest.php?**page**=4)          |
|  | **prev** | NUMBER / NULL (INTEGER) | Number to the previous page for **INPUT** |          Latest Movies (latest.php?**page**=3)          |
| **data** |  | ❌ |                          Parent Key for Data Body                         |          ❌          |
|  | **code** | BASE64ENCODE (MEDIUM STRING) | Encryption text code for **INPUT** |          Post (post.php?**query**=c2hlcGFyZC0yMDIw)          |
|  | **title** | STRING | Title of Movies |          ❌          |
|  | **image** | BASE64ENCODE (LONG STRING) | Image poster of movies (contains long character, maybe make ur loading is to bad) ⚠ |          ❌          |

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
|  **page**  |  NUMBER / NULL (INTEGER)  | yourdomain.com/latest.php?**page**=7 |     ❌    |     ✔    |


## OUTPUT

Result after send data to Latest Movies

```json http
{
  "method": "get",
  "url": "https://xx5k25zsyd.herokuapp.com/latest.php",
  "headers": {}
}
```