---
tags: [search, movies, grabutxxi, docsxxi]
---

# Search

Fetching Data from Movies Search

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

|    🗝    |       ➖      |               ✏              |                                          📝                                         |            INPUT            |
| :------: | :----------: | :--------------------------: | :---------------------------------------------------------------------------------: | :-------------------------: |
| **page** |              |               ❌              |                              Parent Key for Pagination                              |              ❌              |
|          | **isPaging** |    TRUE / FALSE (BOOLEAN)    |                      Does it have discrete pages for **INPUT**                      | ❌ |
|          |   **next**   |    NUMBER / NULL (INTEGER)   |                        Number to the next page for **INPUT**                        | Movies Search (search.php?**page**=4) |
|          |   **prev**   |    NUMBER / NULL (INTEGER)   |                      Number to the previous page for **INPUT**                      | Movies Search (search.php?**page**=3) |
| **data** |              |               ❌              |                               Parent Key for Data Body                              |              ❌              |
|          |   **code**   | BASE64ENCODE (MEDIUM STRING) |                          Encryption text code for **INPUT**                         |       Post (post.php?**query**=c2hlcGFyZC0yMDIw)       |
|          |   **title**  |            STRING            |                                   Title of Movies                                   |              ❌              |
|          |   **image**  |  BASE64ENCODE (LONG STRING)  | Image poster of movies (contains long character, maybe make ur loading is to bad) ⚠ |              ❌              |

## INPUT

Send input data to Movies Search

<!-- theme: info -->

> ##### **Emoji Tags**
>
> **🗝 = KEY**
>
> **✏ = VALUE**
>
> **✍ = EXAMPLE**

|     🗝    |                 ✏                 |                            ✍                           | REQUIRED | OPTIONAL |
| :-------: | :-------------------------------: | :----------------------------------------------------: | :------: | :------: |
| **query** | TEXT TO MOVIES (STRING) |       yourdomain.com/search.php?**query**=batman      |     ✔    |     ❌    |
|  **page** |      NUMBER / NULL (INTEGER)      | yourdomain.com/search.php?**query**=batman&**page**=3 |     ❌    |     ✔    |

## OUTPUT

Result after send data to Movies Search

```json http
{
  "method": "get",
  "url": "https://xx5k25zsyd.herokuapp.com/search.php",
  "query": {
    "query": "batman"
  }
}
```
