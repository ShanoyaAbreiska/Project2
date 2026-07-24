# SQL CRUD & Advanced Query Practice

## Deskripsi
Project ini berisi latihan pengelolaan database menggunakan MySQL, mulai dari pembuatan skema database, operasi CRUD (Create, Read, Update, Delete), hingga query lanjutan menggunakan JOIN, fungsi agregasi, GROUP BY, dan HAVING.

## Tujuan
- Memahami struktur dan relasi database.
- Mengimplementasikan operasi CRUD.
- Menggunakan JOIN untuk menggabungkan data dari beberapa tabel.
- Menerapkan fungsi agregasi seperti SUM(), COUNT(), dan AVG().
- Menggunakan GROUP BY dan HAVING untuk mengolah data.

## Database
Tabel yang digunakan:
- customers
- products
- categories
- orders

Relasi:
- Satu kategori memiliki banyak produk.
- Satu customer dapat memiliki banyak order.
- Satu produk dapat muncul pada banyak order.

## Fitur
### CRUD
- Menambahkan data (INSERT)
- Menampilkan data (SELECT)
- Mengubah data (UPDATE)
- Menghapus data (DELETE)

### Advanced Query

- INNER JOIN
- SUM()
- COUNT()
- AVG()
- MIN()
- MAX()
- GROUP BY
- HAVING
- ORDER BY

## Struktur Project

```text
Project2/
├── database.sql
└── README.md
 
```
### Aggregate Function

#### COUNT()
```sql
SELECT COUNT(*) FROM products;
```

#### SUM()
```sql
SELECT SUM(quantity) FROM orders;
```

#### AVG()
```sql
SELECT AVG(price) FROM products;
```

#### MIN()
```sql
SELECT MIN(price) FROM products;
```

#### MAX()
```sql
SELECT MAX(price) FROM products;
```

## Teknologi
- MySQL
- phpMyAdmin
- Visual Studio Code

## Pembelajaran
Pada project ini saya mempelajari pembuatan skema database beserta relasi antar tabel, implementasi operasi CRUD, serta penggunaan INNER JOIN, GROUP BY, HAVING, dan fungsi agregasi (SUM, COUNT, AVG) untuk menghasilkan informasi dari beberapa tabel yang saling berhubungan.