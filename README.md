# api-post

## Instalasi

Jalankan perintah di bawah di folder aplikasi:

```
mim app install api-post
```

## Endpoints

### `GET APIHOST/post`

Mengambil semua post yang terdaftar. Endnpoint ini menerima pagination query ( page, rpp ). Selain itu juga menerima query string `q` untuk memfilter post dari properti `title`.

### `GET APIHOST/post/read/(id|slug)`

Mengambil properti lengkap suatu post.