# Praktikum 5 – Web Service Engineering (WSE)

## Membangun RESTful CRUD API dengan Express.js

**Mata Kuliah** : Web Service Engineering  
**Topik Praktikum** : RESTful CRUD API dengan Express  
**Nama Mahasiswa** : M. Reyhan  
**NIM** : 230104040126  
**Dosen Pengampu** : Muhayat, M.IT

---

## 📌 Deskripsi Praktikum

Praktikum ini berfokus pada pembuatan **RESTful API sederhana menggunakan Express.js** dengan fitur **CRUD (Create, Read, Update, Delete)** untuk satu resource, yaitu **`products`**. Mahasiswa diminta untuk merancang endpoint RESTful, mengimplementasikan server Express, menguji endpoint menggunakan Postman, serta mendokumentasikan hasil pengujian dalam bentuk evidence.

---

## 🎯 Tujuan Praktikum

1. Menjelaskan konsep dasar RESTful API dan resource.
2. Mendesain endpoint CRUD sederhana untuk satu resource.
3. Mengimplementasikan endpoint Create, Read (list & detail), Update, dan Delete.
4. Menguji endpoint menggunakan Postman / Thunder Client.
5. Menuliskan response JSON yang konsisten.
6. Memahami penggunaan status code HTTP (200, 201, 400, 404, 500).
7. Menyimpan kode program dengan struktur folder yang rapi.
8. Mendokumentasikan hasil uji dalam bentuk evidence.

---

## 🧱 Struktur Project

```
P5-CRUD-REST-230104040126
│
├── server.js
├── package.json
├── package-lock.json
├── README.md
├── evidence/
└── node_modules/
```

---

## 🔗 Base URL

```
http://localhost:3000
```

---

## 📑 Desain Endpoint RESTful

| Method | Endpoint      | Deskripsi                                |
| ------ | ------------- | ---------------------------------------- |
| GET    | /products     | Menampilkan seluruh data produk          |
| GET    | /products/:id | Menampilkan detail produk berdasarkan ID |
| POST   | /products     | Menambahkan produk baru                  |
| PUT    | /products/:id | Mengubah data produk                     |
| DELETE | /products/:id | Menghapus produk                         |

---

## 📦 Contoh Request Body (JSON)

### POST / PUT

```json
{
  "name": "Laptop",
  "price": 10000000
}
```

---

## 📤 Standar Response JSON

### Response Sukses

```json
{
  "status": "success",
  "message": "Product created",
  "data": {
    "id": 1,
    "name": "Laptop",
    "price": 10000000
  }
}
```

### Response Error

```json
{
  "status": "error",
  "message": "Product not found"
}
```

---

## 🧪 Pengujian API

Pengujian API dilakukan menggunakan **Postman**, meliputi:

* GET all products
* GET product by ID
* POST product baru
* PUT update product
* DELETE product

Seluruh hasil pengujian disimpan dalam folder **`/evidence`** berupa screenshot.

---

## 📊 Rubrik Penilaian yang Dipenuhi

* Struktur project & file rapi
* Server berjalan tanpa error
* Endpoint CRUD berfungsi semua
* Status code & response JSON sesuai
* Evidence lengkap
* Dokumentasi singkat dan jelas

---

## 📌 Kesimpulan

Melalui praktikum ini, mahasiswa memahami dasar pembuatan RESTful API menggunakan Express.js, mulai dari perancangan endpoint, penggunaan HTTP method dan status code, hingga pengujian API menggunakan Postman. Praktikum ini menjadi dasar penting sebelum mengembangkan API ke tahap yang lebih kompleks.

---

✅ **Seluruh tugas Praktikum 5 telah dikerjakan dan diuji sesuai modul**

# Praktikum 5 – Web Service Engineering (WSE)

## Membangun RESTful CRUD API dengan Express.js

**Mata Kuliah** : Web Service Engineering  
**Topik Praktikum** : RESTful CRUD API dengan Express  
**Nama Mahasiswa** : M. Reyhan  
**NIM** : 230104040126  
**Dosen Pengampu** : Muhayat, M.IT

---

## 📌 Deskripsi Praktikum

Praktikum ini berfokus pada pembuatan **RESTful API sederhana menggunakan Express.js** dengan fitur **CRUD (Create, Read, Update, Delete)** untuk satu resource, yaitu **`products`**. Mahasiswa diminta untuk merancang endpoint RESTful, mengimplementasikan server Express, menguji endpoint menggunakan Postman, serta mendokumentasikan hasil pengujian dalam bentuk evidence.

---

## 🎯 Tujuan Praktikum

1. Menjelaskan konsep dasar RESTful API dan resource.
2. Mendesain endpoint CRUD sederhana untuk satu resource.
3. Mengimplementasikan endpoint Create, Read (list & detail), Update, dan Delete.
4. Menguji endpoint menggunakan Postman / Thunder Client.
5. Menuliskan response JSON yang konsisten.
6. Memahami penggunaan status code HTTP (200, 201, 400, 404, 500).
7. Menyimpan kode program dengan struktur folder yang rapi.
8. Mendokumentasikan hasil uji dalam bentuk evidence.

---

## 🧱 Struktur Project

```
P5-CRUD-REST-230104040126
│
├── server.js
├── package.json
├── package-lock.json
├── README.md
├── evidence/
└── node_modules/
```

---

## 🔗 Base URL

```
http://localhost:3000
```

---

## 📑 Desain Endpoint RESTful

| Method | Endpoint      | Deskripsi                                |
| ------ | ------------- | ---------------------------------------- |
| GET    | /products     | Menampilkan seluruh data produk          |
| GET    | /products/:id | Menampilkan detail produk berdasarkan ID |
| POST   | /products     | Menambahkan produk baru                  |
| PUT    | /products/:id | Mengubah data produk                     |
| DELETE | /products/:id | Menghapus produk                         |

---

## 📦 Contoh Request Body (JSON)

### POST / PUT

```json
{
  "name": "Laptop",
  "price": 10000000
}
```

---

## 📤 Standar Response JSON

### Response Sukses

```json
{
  "status": "success",
  "message": "Product created",
  "data": {
    "id": 1,
    "name": "Laptop",
    "price": 10000000
  }
}
```

### Response Error

```json
{
  "status": "error",
  "message": "Product not found"
}
```

---

## 🧪 Pengujian API

Pengujian API dilakukan menggunakan **Postman**, meliputi:

* GET all products
* GET product by ID
* POST product baru
* PUT update product
* DELETE product

Seluruh hasil pengujian disimpan dalam folder **`/evidence`** berupa screenshot.

---

## 📊 Rubrik Penilaian yang Dipenuhi

* Struktur project & file rapi
* Server berjalan tanpa error
* Endpoint CRUD berfungsi semua
* Status code & response JSON sesuai
* Evidence lengkap
* Dokumentasi singkat dan jelas

---

## 📌 Kesimpulan

Melalui praktikum ini, mahasiswa memahami dasar pembuatan RESTful API menggunakan Express.js, mulai dari perancangan endpoint, penggunaan HTTP method dan status code, hingga pengujian API menggunakan Postman. Praktikum ini menjadi dasar penting sebelum mengembangkan API ke tahap yang lebih kompleks.

---

✅ **Seluruh tugas Praktikum 5 telah dikerjakan dan diuji sesuai modul**
