## AND
### Struktur query
```
select warna,pemilik FROM mobil WHERE warna AND nama_pemilik;
```
### Contoh query
```sql
select warna,pemilik FROM mobil WHERE warna="Hitam" AND pemilik="Fatur";
```
### Hasil

![Gambar_AND](IMG_AND.jpg)
### Analisis
`Select warna` bertugas untuk menampilkan warna dari mobil yang ingin di tampilkan,`from mobil` adalah nama tabel (mobil),`where warna="hitam"` berarti warna mobil yang akan di tampilkan itu warnanya hitam dan `AND` itu menampilkan seluruh mobil yang warnanya hitam dengan nama pemiliknya, walaupun beda pemilik tapi kalau warnanya sama tetap akan tampil.
### Kesimpulan
Jadi kalo kita ingin menampilkan daftar mobil dengan warna hitam beserta nama pemiliknya, cukup menggunakan kode `AND` walaupun pemiliknya itu berbeda yang penting warnanya sama.

---
## OR
### Struktur query
```
```
### Contoh query
```sql
select warna,pemilik FROM mobil WHERE warna="Hitam" OR pemilik="Fatur";
```
### Hasil

![Gambar_OR](asets/IMG_OR.jpg)
### Analisis
### Kesimpulan

---
## BETWEEN
### Struktur query
```

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 150000;
```
### Hasil

![Gambar_BEETWEN](Asets/IMG_BEETWEN.jpg)

### Analisis

### Kesimpulan

---
## NOT BETWEEN
### Struktur query
```

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental NOT  BETWEEN 100000 AND 150000;
```
### Hasil

![Gambar_1](asets/IMG_N.BEETWEN.jpg)
### Analisis
### Kesimpulan

---
## <=
### Struktur query
```

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental <=50000;
```
### Hasil

![Gambar_<=](asets/IMG_2.jpg)
### Analisis
### Kesimpulan

---
## >=
### Struktur query
```

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental >=50000;
```
### Hasil

![Gambar_3](asets/IMG_3.jpg)
### Analisis
### Kesimpulan

---
## <>
### Struktur query
```

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental <> 50000;
```
### Hasil

![Gambar_4](asets/IMG_4.jpg)
### Analisis
### Kesimpulan

---
## !=
### Struktur query
```

```
### Contoh query
```sql
SELECT * FROM mobil WHERE harga_rental !=  50000;
```
### Hasil

![Gambar_5](asets/IMG_5.jpg)
### Analisis
### Kesimpulan

---
## TANTANGAN LOGIN
### Struktur query
```

```
### Contoh query
```sql
select pemilik from mobil where pemilik="Fatur";
```
### Hasil
 
![Gambar_6](asets/IMG_6.jpg)
### Analisis
### Kesimpulan

---