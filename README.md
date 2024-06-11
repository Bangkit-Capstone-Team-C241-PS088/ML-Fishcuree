# Guide menggunakan API PREDICT Fish Disease 📸🐟🏥:

Base url : wait for deployment

---

## Ujicoba koneksi - method GET

url

```
/ping
```

### list response dari server :

- ketika berhasil :

```
{
    "Hello, I am alive"
}
```

---

## Pediksi Gambar Ikan - method POST

url

```
/predict
```

request payload data :

```
{
    "file" : [file gambar user]
}
```

### list response dari server :

- ketika berhasil :

```
{
    "class": "[jenis penyakit]",
    "confidence": [nilai akurasi]
}
```

---
