
# Struktur awal Tabel

![Struktur awal tabel](Struktur_awal_table.jpg)

# Menambahkan kolom 
## Struktur query 
```sql
ALTER TABLE nama_tabel ADD batas_peminjaman varchar(10) AFTER nama_kolom;
```
## Contoh Query 
```sql
ALTER TABLE mobil ADD batas_peminjaman varchar(10) AFTER peminjam;
```

## Hasil 

![Menambah kolom](Menambahkan_kolm.jpg)
## Analisis 


## Kesimpulan 


## Tambahan

### Query 
```sql
Update mobil SET batas_peminjaman="2024-04-24" WHERE peminjam is NOT NULL;
```

### Hasil
![Tambahan](Query_tambhan.jpg)



# Mengubah nama kolom
## Struktur query 
```sql

```
## Contoh Query 
```sql
ALTER TABLE mobil RENAME COLUMN batas_peminjaman TO deadline;
```

## Hasil 

![ubah nama_kolom](ubah_nama_kolom.jpg)
## Analisis 
## Kesimpulan 

# Mengubah Tipe data kolom
## Struktur query 
```sql

```
## Contoh Query 
```sql
ALTER TABLE mobil MODIFY deadline DATE;
```

## Hasil 

![mengubah tipe data kolom](ubah_tipedata.jpg)
## Analisis 


## Kesimpulan
