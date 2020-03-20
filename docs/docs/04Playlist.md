---
tags: [movies, playlist, grabutxxi, docsxxi]
---

# Playlist

Fetching Data from Movies Playlist

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

|     🗝    |               ✏              |                 📝                 |        INPUT        |
| :-------: | :--------------------------: | :--------------------------------: | :-----------------: |
|  **code** | BASE64ENCODE (MEDIUM STRING) | Encryption text code for **INPUT** | Post (post.php?**query**=c2hlcGFyZC0yMDIw) |
| **title** |            STRING            |           Title of movies          |          ❌          |

## INPUT

Send input data to Movies Playlist

<!-- theme: info -->

> ##### **Emoji Tags**
>
> **🗝 = KEY**
>
> **✏ = VALUE**
>
> **✍ = EXAMPLE**

|     🗝    |                      ✏                     |                                    ✍                                   | REQUIRED | OPTIONAL |
| :-------: | :----------------------------------------: | :--------------------------------------------------------------------: | :------: | :------: |
| **query** | **code** of Movies Archive (MEDIUM STRING) | yourdomain.com/playlist.php?**query**=ZXhvcmNpc20tbW92aWVzLXBsYXlsaXN0 |     ✔    |     ❌    |

## OUTPUT

Result after send data to Movies Playlist

```json http
{
  "method": "get",
  "url": "https://xx5k25zsyd.herokuapp.com/playlist.php",
  "query": {
    "query": "ZXhvcmNpc20tbW92aWVzLXBsYXlsaXN0"
  }
}
```
