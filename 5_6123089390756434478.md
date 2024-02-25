---
color: "#20bf6b"
---
# Judul
## Sub Judul
Jika kita membuat judul maka secara otomatis judul dan konten akan berbentuk **menu accordion**

```
# Judul
## Sub Judul
Jika kita membuat judul maka secara otomatis judul dan konten akan berbentuk **menu accordion**
```
# Pemformatan Teks
- *Italic* : Blok teks dan ketik `SHIFT + *`  atau `SHIFT + _` 
- **Bold** : Blok teks dan ketik `SHIFT + * + *`  atau `SHIFT + _ + _`
- ***Bold Italic*** : Blok teks dan ketik `SHIFT + * + * + *`  atau `SHIFT + _ + _ + _`
- ==Highlight Text== : Blok teks dan ketik `==` 
- ~~Striketrought Text~~ : Blok teks dan ketik `SHIFT + ~ + ~`

```
- *Italic* : Blok teks dan ketik `SHIFT + *`  atau `SHIFT + _` 
- **Bold** : Blok teks dan ketik `SHIFT + * + *`  atau `SHIFT + _ + _`
- ***Bold Italic*** : Blok teks dan ketik `SHIFT + * + * + *`  atau `SHIFT + _ + _ + _`
- ==Highlight Text== : Blok teks dan ketik `==` 
- ~~Striketrought Text~~ : Blok teks dan ketik `SHIFT + ~ + ~` 
```
# List dan Garis Bawah
## List Berurut
Jika ingin membuat list berurut seperti di bawah ini maka cukup dengan mengetik angkanya lalu kemudian diikuti dengan tanda titik "." dan spasi. Contohnya seperti berikut:
1. Bangun Tidur
2. Mandi
3. Makan
4. Kerja
5. Pulang
6. Tidur

> [! Garis Bawah]
> Jika ingin membuat garis bawah hanya perlu mengetikkan `"---","__","***"`

---
## List  Tidak Berurut
Jika ingin membuat list tanpa memperhatikan urutan seperti maka cukup dengan mengetik "-" lalu kemudian diikuti dengan spasi. Contohnya seperti berikut:
- Apel
- Mangga
- Jeruk
- Stroberi
- Jambu
# Ceklis
- [] Ketik "-" lalu "[ ]" untuk membuat cheklist point
- [x] Tambahkan "x" dalam "[]" untuk mencoret checklist di awal
```
- [ ] : Ketik "-" lalu "[ ]" untuk membuat cheklist point
- [x] : Tambahkan "x" dalam "[]" untuk mencoret checklist di awal
```
# Blockquotes dan Cards
> Ketik ">" dan spasi untuk  membuat blockquotes
```
> Ketik ">" dan spasi untuk  membuat blockquotes
```

> [!faq]- Are callouts foldable? 
> > Yes! In a foldable callout, the contents are hidden when the callout is collapsed.

```
> [! faq]- Are callouts foldable? 
> > Yes! In a foldable callout, the contents are hidden when the callout is collapsed.
```

> [!question] Can callouts be nested?
> > [!todo] Yes!, they can. 
> > > [!example] You can even use multiple layers of nesting.

```
> [!question] Can callouts be nested?
> > [!todo] Yes!, they can. 
> > > [!example] You can even use multiple layers of nesting.
```

> [!INFO]
Lorem Ipsum Dolor Sit Amet

```
> [!INFO]
Lorem Ipsum Dolor Sit Amet
```

>[!NOTE]
>Lorem Ipsum Dolor Sit Amet

```
>[!NOTE]
>Lorem Ipsum Dolor Sit Amet
```

>[!WARNING]
Lorem Ipsum Dolor Sit Amet

```
>[!WARNING]
Lorem Ipsum Dolor Sit Amet
```

> [!danger] 
> Lorem ipsum dolor sit amet

```
> [!danger] 
Lorem ipsum dolor sit amet
```

>[!TIP]
Lorem ipsum dolor sit amet

```
>[!TIP]
Lorem ipsum dolor sit amet
```

> [!example] 
> Lorem ipsum dolor sit amet

```
> [!example] 
Lorem ipsum dolor sit amet
```

> [!quote] 
> Lorem ipsum dolor sit amet

```
> [!quote] 
Lorem ipsum dolor sit amet
```
# Source Code 
Berikut adalah sebuah kode ` html ` dan` Javascript `. Caranya adalah dengan menggunakan **backtick sekali** untuk satu baris seperti contoh penulisan html dan javascript pada kalimat sebelumnya. Adapun untuk kode multi baris mengetikkan **backtik 2 kali**.
```html
<html>
	<head>
	</head>
	<body>sdjidjids</body>
</html>
```

```js 
function fancyAlert(arg) {
	if(arg) { $.facebox({div:'#foo'}) }
} 
```
# File
## Gambar, Video, Audio


![Logo SMKN 7 Makassar](assets/logo-smk7.png)
```
![Logo SMKN 7 Makassar].(assets/logo-smk7.png).
```

Untuk mengatur ==lebar== dan ==tinggi== gambar silahkan tambahkan nilai opsional di dalam judul gambar, misalnya gambar ingin diatur dengan nilai lebarnya sebesar ==250 pixel== dan tingginya sebesar ==300px==, maka seperti ini:
```
![Logo SMKN 7 Makassar|250x300].(assets/logo-smk7.png).
```

## Link
Shortcut yang dapat digunakan untuk membuat link yaitu `CTRL+K`

[link google](https://www.google.com)

```
[link google].(https://www.google.com).
```

[Halaman Lain](Page%20Test.md)

```
[Halaman Lain].(Page%20Test.md).
```

![](https://www.youtube.com/watch?v=NnTvZWp5Q7o)

```
![](https://www.youtube.com/watch?v=NnTvZWp5Q7o)
```
# Tabel
- Menggunakan Plugin **Advance Table**
	1.  Install terlebih dulu plugin **Advance Table** pada community plugins di tab settings
	2. Setelah terinstal, **enable plugin** tersebut
	3. **Buat tabel**, dengan cara mengetik "|" lalu isian data kemudian tekan "tab" untuk buat kolom baru dan tekan "enter"
	**Contoh:**
	
	| No  | Nama    |  Kelas   |
	|:---:| ------- |:--------:|
	|  1  | Ibrahim | XI RPL 2 |
	|  2  | Saleh   | XI RPL 1 |
	|  3  | Fajar   | XII RPL  |
	
- Menggunakan Plugin **DataLoom**
	1. Install terlebih dulu plugin **Advance Table** pada community plugins di tab settings
	2. Setelah terinstal, **enable plugin** tersebut
	3. Pada navigasi bar, pilih icon **create new loom**
	4. Lalu silahkan buat tabel sesuka hati
	5. Pilih menu "titik tiga" dipojok kanan dan klik **export** lalu pilih markdown. Selanjutnya hasil tabel akan dikonversikan dalam bentuk markdown yang dapat dicopy ke note
	**Contoh:**
	
	| No  | Barang  | Kualitas | Harga      |
	| --- | ------- | -------- | ---------- |
	| 1   | Sapu    | Baik     | $20,000.00 |
	| 2   | Colokan | Rusak    | $30,000.00 |
# Hastag
Langsung saja ketik # dan teksnya
#hastag #newhastag #hastaglagi
# Footnote
Ini buat footnote referensi [^1]. 
Ini buat footnote refrensi lagi bacaan lagi [^2].
```
Ini buat footnote referensi [^1]. 
Ini buat footnote refrensi lagi bacaan lagi [^2].

[^1]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[^2]: https://github.com/endymuhardin/buku-pandoc/tree/master/buku
```
# Shortcut Paling Berguna
- `CTRL + P` : Menampilkan perintah dan menjalankannya
- `CTRL + E` : Mengubah tampilan note menjadi mode editing atau ke mode preview
- `CTRL + K` : Membuat link
- `CTRL + SHIFT + P` ==(Custom Hotkeys)==: Mengkonversi note ke bentuk PDF 
- `CTRL + SHIFT + ->` ==(Custom Hotkeys)==: Split note ke sisi kanan
- `CTRL + SHIFT + Arrow Bawah` ==(Custom Hotkeys)==: Split note ke sisi bawah
- `CTRL + or CTRL -` : Memperbesar / memperkecil tampilan note
- `CTRL + F` : Mencari kata kunci di dalam note
- `CTRL + H` : Melakukan replace kata di dalam note

# Rekomendasi Plugin
Silahkan masuk di :
1. Setting
2. Community plugins
3. Klik turn on browse (community plugins)
4. Cari plugin
5. Install lalu setelah terinstall klik enable

Berikut plugin rekomendasinya:
1. ***Advanced Tables***
	Membuat tabel yang caranya sudah dijelaskan sebelumnya pada poin tabel.
2. ***Make.md***
	Memberikan tooltip untuk pemformatan teks serta dapat membuat atau menyisipkan properti pada note.
3. ***Data Loom***
	Membuat tabel tetapi dengan UI yang mudah.
3. ***Advanced Slides***
	Mengkonversikan note menjadi slide.
4. ***Excelidraw***
	Sebagai canvas sederhana untuk membuat diagram alir atau sketsa sederhana dan yang semisalnya.
5. ***Projects***
	Dapat membuat folder notes dalam bentuk projects yang formatnya bisa berupa table, board, calendar, gallery.
6. ***Icon Folder***
	Mengatur icon notes berdasarkan selera. Tinggal download sumber iconnya di plugin. Lalu pilih folder/file yang ingin diubah iconnya, klik kanan dan change icon.
# Prana Luar
[^1]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
 [^2]: https://github.com/endymuhardin/buku-pandoc/tree/master/buku