---
tags: [movies by, country, grabutxxi, docsxxi]
---

# Movies by Country

Fetching Data from Movies by Country

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
|          |   **next**   |    NUMBER / NULL (INTEGER)   |                        Number to the next page for **INPUT**                        | Movies by Country (country.php?**page**=4) |
|          |   **prev**   |    NUMBER / NULL (INTEGER)   |                      Number to the previous page for **INPUT**                      | Movies by Country (country.php?**page**=3) |
| **data** |              |               ❌              |                               Parent Key for Data Body                              |              ❌              |
|          |   **code**   | BASE64ENCODE (MEDIUM STRING) |                          Encryption text code for **INPUT**                         |       Post (post.php?**query**=c2hlcGFyZC0yMDIw)       |
|          |   **title**  |            STRING            |                                   Title of Movies                                   |              ❌              |
|          |   **image**  |  BASE64ENCODE (LONG STRING)  | Image poster of movies (contains long character, maybe make ur loading is to bad) ⚠ |              ❌              |

## INPUT

Send input data to Movies by Country

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
| **query** | **code** of Country (MEDIUM STRING) |       yourdomain.com/country.php?**query**=VVNB      |     ✔    |     ❌    |
|  **page** |      NUMBER / NULL (INTEGER)      | yourdomain.com/country.php?**query**=VVNB&**page**=3 |     ❌    |     ✔    |

## OUTPUT

Result after send data to Movies by Country

```json http
{
  "method": "get",
  "url": "https://xx5k25zsyd.herokuapp.com/country.php",
  "query": {
    "query": "VVNB"
  }
}
```
