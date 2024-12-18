# 1. KESIMPULAN DARI VIDEO
Sejarah **web** dimulai pada tahun 1990an ketika **Tim Berners Lee** menciptakan konsep sistem yang menghubungkan dokumen melalui internet. **Berners Lee** juga menciptakan protokol **HTTP** dan **HTML** sebagai (**hyperText** **markup language**) untuk memformat teks. Browser pertama, **World Wide Web** (www), diciptakan oleh **Berners Lee**. **HTML** digunakan untuk struktur halaman web dengan tag `<html>`, `<head>`, dan `<body>`.**CSS** (**CASSADING STYLE SHEETS**), yang lahir pada tahun 1994 diciptakan oleh **Hakon Wium Lie**, **memisahkan styling** dan **struktur HTML**. terbagi Menjadi 2 yaitu **General** dan **Spesifik**.


## Sejarah atau terciptanya web

### diciptakan oleh 
**Tim Berners Lee** Pada tahun 1990an

**Berners Lee** Menciptakan Suatu Konsep Sisitem yang memungkinkan sebuah dokumen bisa terhubung satu sama lain melalui internet.
**Bernest Lee** juga nyiptain protokol http yang jadi jembatan antara Server dan Client untuk saling mengirim data. 

### HTML BUKAN BAHASA PEMROGRAMAN TAPI "MARKUP LANGUAGE"
Bernest Lee Ciptakan HTML Sebagai Bahasa untuk MarkUp atau Simpelnya Ngeformatin teks jadi lebih rapih dan lebih terstruktur.
## Menciptakan Browser Pertama
**Bernest Lee Menciptakan Browser Pertama** yang bernama **world Wide** web atau **www** yang sampai saat ini nama **www** ini kita sering temui di website. 

## KEGUNAAN HTML 
1. Setiap Halaman Akan dimulai dengan Tag `<html> </html>` 
2. Di dalam Tag "html" Ada Yang Namanya `<head> </head>` dan ada yang namanya `<body> </body>` Untuk Menyimpan Komponen - Komponen Website Seperti Teks, heading,paragraf,tabel,dll Contohnya `<body> Isi Komponen - Komponen Sesuai Keinginan Anda </body>
3. Ada Yang Namanya `<title> </title>` yang berisikan judul Website/header, Contohnya `<title> Judul Web </title>` 

## CSS 
 **CSS** (CASSADING STYLE SHEETS) lahir pada tahun 1994 dan diciptakan oleh **Hakon Wium Lie.CSS** bertujuan agar styling dan struktur HTML yang terpisah dan menjadi lebih mudah untuk dipelihara sampai saat ini.CSS juga terbagi Menjadi 2 yaitu General dan Spesifik.


___







# 2. Deskripsikan html,CSS,Java script dari sebuah rumah 

## Contoh
![Gambar_deskripsi](Assets/deskripsi.jpg)

## DESKRIPSI 

- **HTML** adalah bagian kerangka atau pondasi awal untuk membuat sebuah rumah.
- **CSS** adalah desain awal dari sebuah rumah seperti cat,atap rumah,jendela,pintu,dan cerobong asap.
- **JAVA SCRIPT** adalah sebuah interaksi dari sebuah rumah yang dimana di cerobong asapnya mengeluarkan rumah mungkin sedang memasak,dan cahaya lampu yang keluar dari jendela yang menunjukkan sebuah aktivitas di dalam rumah seperti menyalakan saklar lampu.




___






# 3.  Pengenalan HTML 


```html
<!DOCTYPE html>
<html>
<head>
<title>ini adalah judul</title>
</head>
<body>
<p>ini adalah paragraf yang ditampilkan di browser</p>
</body>
</html>
```

```html
<!DOCTYPE html>
<html>
<head>
<title>ini adalah judul</title>
</head>
<body>
<p>pilihan hanya ada 2, tempe dan tahu</p>
<p>kesuksesan itu seperti banyak nya tempe</p>
<p>tidak ada yang tau</p>
</body>
</html>
```

•==Tag== <!DOCTYPE html> memberitahukan web browser bahwa dokumen HTML adalah versi 5

• ==Tag== pembuka `<Html>` menandai awal sebuah dokumen HTML sampai dengan tag penutup `</html>`

• ==Tag== pembuka` <head>` berisi informasi tentang halaman HTML sampai dengan tag penutup `</head>`,biasanya dalam tag head terdapat tag `<title>` untuk memberikan informasi judul halaman HTML

• Apapun tag yang berada di antara tag pembuka `<body>` sampai dengan tag penutup `</body> `akan tampil di web browser.

**Hasil**:

![Gambar_30](Assets/IMG_30.jpg)


# Anatomi Elemen HTML
**Elemen** adalah suatu kesatuan dan sebuah Tag yang dimulai dari ==Tag pembuka== hingga ke ==Tag penutup==. Elemen HTML secara garis besar terdiri atas tiga bagian yaitu **Tag pembuka**, **konten/Isi tag**, dan **tag penutup**>.

**Contoh:**

![Gambar_ahref](Assets/IMG_ahref.jpg)


```html
<a href="https://youtu.be/8D_FgidOgkY?si=VNXzvJL4y4XaEs_L"> klik untuk login</a>
```

**Hasil anatomi HTML**:

![Gambar_00](Assets/IMG_00.jpg)



___


# Tag pembuka & Penutup 

### **Tag Pembuka** 
`<a` adalah Tag pembuka,digunakan untuk membuat sebuah Hyperlink atau tautan yang dapat di klik untuk menuju ke halaman web lain.

### **Tag Penutup**
`/a>` digunakan untuk menutup/mengakhirinya sebuah Tag.


# Atribut Tag
`href` adalah nama sebuah atribut.Digunakan untuk menentukan sebuah tautan atau URL,dan dapat mengarahkan kita ke halaman link video di YouTube seperti:
https://youtu.be/8D_FgidOgkY?si=VNXzvJL4y4XaEs_L

## Nilai Atribut
https://youtu.be/8D_FgidOgkY?si=VNXzvJL4y4XaEs_L adalah Nilai Atribut.Sebagai Tautan atau URL alamat web ke halaman sebuah video di Dengan menaruh URL ini ke dalam atribut `href`tag html` <a>`,tautan tersebut ketika kita klik akan otomatis menuju ke halaman YouTube.
`Klik untuk melihat video`adalah konten atau isi tag yang berfungsi sebagai petunjuk bagi pengguna untuk mengetahui bahwa link tersebut akan membawa mereka ke halaman YouTube.

# Konten atau Isi Tag
Teks `klik untuk melihat video` adalah yang akan muncul sebagai tautan dihalaman web,ketika kita klik kita akan di arahkan ke tautan yang sudah ditentukan dalam sebuah atribut `href`.


# Tag Dasar
## Heading 
`<h1> ` **sampai** ` <h6>`

**Penjelasan:**

Tag dasar `<h1> `sampai `<h6>` digunakan untuk membuat Heading atau judul pada halaman web.Heading `<h1> `adalah yang paling tinggi, sedangkan `<h6>` adalah yang terendah. Semakin tinggi level Heading maka semakin kecil ukuran teksnya contohnya:
`<h1>` = Heading Level 1
`<h2>`= Heading Level 2
`<h3>`= Heading Level 3
`<h4>`= Heading Level 4
`<h5>`= Heading Level 5
`<h6>`= Heading Level 6

**Struktur**
```html
<p><h1></h1></p>
<p><h2></h2></p>
<p><h3></h3></p>
<p><h4></h4></p>
<p><h5></h5></P>
<p><h6></h6></p>
```

**Kode Program**

```html
<p><h1>yang ini h1</h1></p>
<p><h2>yang ini h2</h2></p>
<p><h3>yang ini h3</h3></p>
<p><h4>yang ini h4</h4></p>
<p><h5>yang ini h5</h5></P>
<p><h6>yang ini h6</h6></p>
```


>[!faq]- Hasil program Heading 
>![Gambar_45](Assets/IMG_45.jpg)

## **Paragraf** 

### `<p>`

Tag `<p>` dalam HTML digunakan untuk membuat paragraf Teks,dan dapat memberikan struktur yang terorganisir pada halaman web.Tag `</p>` merupakan tag penutup pada elemen paragraf.

**Struktur** 
```html
<p>-</p>
<p>-</p>
<p>-</p>
```

**Kode program** 

```html
<p>pilihan hanya ada 2, tempe dan tahu</p>
<p>kesuksesan itu seperti banyak nya tempe</p>
<p>tidak ada yang tau</p>

```

**Hasil dari Program**
>[!faq]- Hasil program tag `<P>`
>![Gambar_30](Assets/IMG_30.jpg)


___


### `<b>`
 
 Tag `<b>` adalah untuk membuat tulisan menjadi bold/tebal.Tag penutup `</b>` digunakan untuk mengakhiri efek bold/tebal.
 
 
**Struktur** 
```html
<p><b>-</b></p>
<p><b>-</b></p>
<p>-</p>!
```

**Kode Program 

```html
<p><b>untuk membedakan tulisan mana yang memakai Bold</b></p>
<p><b>Tulisan ini memakai Bold</b></p>
<p>tulisan tidak memakai Bold</p>!
```

>[!faq]- Hasil program tag `<b>`
>![Gambar_31](Assets/IMG_31.jpg)



___








### `<u>`

Tag `<u>` digunakan untuk memberikan garis di bawah teks atau menggaris bawahi sebuah teks dan tag `</u>` sebagai penutup garis bawah teks.

**Struktur** 
```html
<p><u>-</u></p>
<p><u>-</u></p>
<p>-</p>
```

**Kode Program**

```html
<p><u>untuk membedakan tulisan mana yang memakai garis bawah</u></p>
<p><u>Tulisan ini memakai garis bawah</u></p>
<p>tulisan tidak memakai garis bawah</p>
```


>[!faq]- Hasil program tag `<u>`
>![Gambar_35](Assets/IMG_35.jpg)



___

### `<i>`

- Tag `<i>` digunakan untuk memberikan efek italic pada teks dan diakhiri dengan tag `</i>`

**Struktur** 
```html
<p><i>-</i></p>
<p><i>-</i></p>
<p>-</p>
```

**Kode Program** 

```html
<p><i>untuk membedakan tulisan mana yang memakai efek italic</i></p>
<p><i>Tulisan ini memakai efek italic</i></p>
<p>tulisan tidak memakai efek italic</p>
```

>[!faq]- Hasil program tag `<i>`
>![Gambar_32](Asets/IMG_32.jpg)



___

### `<br>`

Tag `<br> ` untuk membuat baris baru dan diakhiri dengan tag `</br>`.

**Struktur** 
```html
<p>-</p><br>
<p>-</p><br>
<p>-</p><br>
```

**Kode Program

```html
<p>ini adalah baris pertama</p><br>
<p>ini adalah baris kedua</p><br>
<p>ini adalah baris ketiga</p><br>
```

**hasil dari program**

>[!faq]- Hasil program tag `<br>`
>![Gambar_33](Assets/IMG_33.jpg)

___

### Atribut `align`

**Penjelasan**

Atribut `align` berguna untuk mengontrol perataan pada halaman web
`align="left"` akan membuat paragraf menjadi rata kiri.
`align="right"` akan membuat paragraf menjadi rata kanan.
`Align="center"` akan membuat paragraf menjadi rata tengah.
`align="justify"`akan membuat paragraf rata kanan dan kiri.



**Kode program** 

```html
<h3>Belajar Menggunakan Elemen Tag HTML p</h3>
<p align="left">
Sebuah rumah yang berisikan satu keluarga yaitu,ayah,ibu,dan 3 anaknya.</p>
<p align="right">
Sebuah rumah yang berisikan satu keluarga yaitu,ayah,ibu,dan 3 anaknya.</p>
<p align="center">
Sebuah rumah yang berisikan satu keluarga yaitu,ayah,ibu,dan 3 anaknya.</p>
<p align="justify">
Sebuah rumah yang berisikan satu keluarga yaitu,ayah,ibu,dan 3 anaknya.</n>

```

**Hasil dari Program**

>[!faq]- Hasil
>![Gambar_34](Assets/IMG_34.jpg)

___
## **Komentar** 

Html juga mempunyai Tag khusus untuk komentar.Untuk membuat komentar di HTML kita pakai awalan `<!--` dan penutup 
`-->`.

> [!faq] !! Komentar tidak akan di tampilkan pada halaman website namun programmer biasanya menggunakan komentar untuk memperjelas kode program




**Kode program**

```html
<!-- ini komentar,tidak akan tampil di browser -->
<p>ini bukan komputer, dan akan tampil di browser</p>
```


**Hasil dari Program**

![Gambar_9](Assets/IMG_9.jpg)


___

## **LIST**
List adalah fungsi dalam HTML yang digunakan untuk menampilkan daftar dari sesuatu.Tag HTML terdiri dari 2 jenis ,`<ol>` ordered list (berurutan),dan `<ul> `urdered list (tidak berurutan). oredered list `<ol>` akan ditampilkan dengan angka atau huruf sedangkan undered list `<ul>`dengan bulatan atau kotak ataupun simbol lainnya.

>[!info] !! Untuk menampilkan list dalam HTML dapat menggunakan tag `<ol>`...`<\ol>` atau` <ul>`...`</ul>`namun perlu dengan menyisipkan elemen `<li>` untuk membuat daftar list

**Struktur** 
```html
Undered list

<h1></h1>
<ul>
<li></Li>
<li></Li>
<li></Li>
<li></Li>
<li></Li>
</ul>

Ordered list

<h1></h1>
<ol>
<li></Li>
<li></Li>
<li></Li>
<li></Li>
<li></Li>
</ol>

```

**Kode program**

```html
Undered list

<h1>list peralatan kelas</h1>
<ul>
<li>Sapu</Li>
<li>pel</Li>
<li>dispenser</Li>
<li>kipas</Li>
<li>gelas</Li>
</ul>

Ordered list

<h1>list Kalimat</h1>
<ol>
<li>Ini kalimat pertama</Li>
<li>ini kalimat kedua</Li>
<li>ini kalimat ketiga</Li>
<li>ini kalimat ke empat</Li>
<li>ini kalimat ke lima</Li>
</ol>


```


**Hasil dari Program**:

**Undered list**:

![Gambar_10](Assets/IMG_10.jpg)

**Ordered list**:

![Gambar_11](Assets/IMG_11.jpg)


___

## Link
 tag `<a>` adalah target.`href` berisi alamat yang dituju. `href` adalah singkatan dari **Hypertext Reference**. Atribut `target` menentukan tempat untuk membuka dokumen yang ditautkan didalam `target` ada `blank` yang berfungi untuk membuka tautan di tab baru dan ditutup dengan `</a>`.

Contoh :
```html
<h3>Menggunakan Tag Anchor</h3>
<a href ="https://www.google.com" target="_blank">klik disini untuk ke google</a><br>
<a href ="halaman_lain.html">klik disini untuk ke halaman lain yang saya buat!</a>
```


![Gambar-13](Assets/IMG_12.jpg)


## Multimedia
### Gambar
Dalam HTML gambar didefinisikan dengan tag `<img>` . Tag `<img>` adalah tag kosong, hanya berisi atribut saja, dan tidak memiliki tag penutup. 

Atribut `src` berfungsi untuk menentukan URL (alamat web) dari gambar yang ingin ditampilkan. 

Atribut `alt` menyediakan teks alternatif untuk gambar, jika pengguna karena beberapa alasan tidak dapat melihatnya (karena koneksi lambat, kesalahan pada atribut `src` ,atau jika web browser telah disetting untuk tidak menampilkan gambar). Jika browser tidak dapat menentukan gambar, maka akan muncul nilai pada atribut `alt` . 

Dalam tag `<img>` terdapat juga atribut `width` dan `height` untuk mengatur ukuran gambar, pada versi HTML5 standar satuan ukuran gambar adalah pixel. 

- Misalnya dalam folder root terdapat file gambar bernama logo.png. untuk menampilkan gambar tersebut kita hanya perlu mengisi nama gambar beserta jenis ekstensi file gambar ke dalam atribut `src` , Contohnya `src = "logo.png"` 
- untuk menampilkan dari internet carilah link gambar yang akan ditampilkan lalu masukkan dalam nilai atribut `src` , contohnya **`https://namasitus.com/gambar.png`**

**Contoh kode program :**
```html
<img src="logo SMKN7 MAKASSAR.png" alt="Logo SMKN7 MAKASSAR" width="400" height="400">
```


>[!faq]- hasil program gambar 
>![Gambar_13](Assets/IMG_13.jpg)



>[!faq]- screenshot folder 
![Gambar_14](Assets/IMG_14.jpg)

___

### vidio
Fitur HTML 5 mencakup dukungan audio dan video asli tanpa memerlukan flash. tag `<audio>` dan `<vidio>` mempermudah penambahan media ke dalam halaman web. Yang penting untuk diatur pada tag ini adalah atribut `src` yang berfungsi untuk mengidentifikasi sumber media. Selain itu, terdapat pula atribut `controls`agar pengguna dapat memutar dan menjeda media.

**Contoh** :
```html
<video src="Pes.mp4.mp4"controls width="400"></video>
```

>[!faq]- hasil program `video src`
>![Gambar15](Assets/IMG_15.jpg)



### Audio

Seperti yang telah dibahas sebelumnya bahwasanya tag `<audio>` merupakan bagian fitur HTML5 untuk menampilkan audio asli dihalaman web tanpa memerlukan flash sebagaimana pada HTML versi 4. Yang penting untuk diatur pada tag ini adalah atribut `src` yang berfungi untuk mengidentifikasi sumber media. Selain itu, terdapat pula atribut `controls` agar pengguna dapat memutar dan menjeda media. 

**Contoh :** 

```html 
<audio src="audio03.mp3" controls >
  Browser anda tidak mendukung elemen 
  <audio>.</audio>
```


> [!INFO]
> Konten berupa teks "Browser anda tidak mendukung elemen `<audio>`." Pada tag `<audio>` akan ditampilkan jika browser tidak mendukung elemen tersebut. Sehingga sebenarnya bagian ini dapat dihilangkan.


>[!faq]- Hasil program audio
>![Gambar_16](Assets/IMG_16.jpg)




### Halaman web lain
 Elemen <`iframe>` dapat digunakan untuk menampilkan halaman website lain dalam suatu website. Atau menampilkan dokumen html lain dalam sebuah website. Mudahnya, bisa dibilang website dalam website

Contoh penggunaannya seperti ini. Jika kita mempunyai website sekolah, lalu di website tersebut ingin menampilkan alamat dalam google maps sekolah. Agar memudahkan pengunjung website,kita bisa langsung tampilkan saja halaman sekolah yang ada digoogle maps

Dalam tag `iframe` ada beberapa atribut yang penting seperti : 
- `src`,untuk mencari sumber halaman html atau web yang akan ditampilkan didalam frame
- `width` dan `height`, untuk mengatur ukuran panjang dan lebar dari frame.


**Kode program**

```html
<iframe src="https://smkn7makassar.sch.id/"
width="300" height="600"</iframe>
```


> [!faq]- Hasil program `i frame`
> ![Gambar_17](Assets/IMG_17.jpg)
> 


## **Tabel**
Tabel dalam HTML didefinisikan dengan tag `<table>`.
- `<tr>` berfungsi untuk membuat baris tabel.
- Header/judul tabel didefinisikan dengan tag `<th>`.Secara default, header tabel memiliki teks tebal dan berada di tengah.
- Data tabel/sel didefinisikan dengan tag `<td>`karena sel merupakan bagian terkecil dari tabel maka dari itu tag ini selalu berada di dalam tag `<tr>`.

**Contoh**

```html
<table Border="1">
<tr>
  <th>nama</th>
  <th>asal industri</th>
</tr>
<tr>
  <td>Fathur</td>
  <td>Fajar TV</td>
</tr>
<tr>
  <td>Muh.Taufik</td>
  <td>Fajar TV</td>
</tr>
```


 **hasil program Tabel**:
 
![Hasil tabel](Assets/IMG_99.jpg)



Selain itu,terdapat beberapa atribut tabel yang Penting untuk diketahui yaitu:

- `rowspan` merupakan atribut dari HTML yang berfungsi untuk menggabungkan beberapa baris (kebawah).
- `colspan` atau colomn span merupakan atribut HTML yang berfungsi untuk menggabungkan beberapa kolom (ke samping).
- `width` adalah untuk mengatur lebar tabel yang nilainya didefinisikan dalam satuan pixel secara default.
- `height` berfungsi mengatur tinggi sebuah tabel yang nilainya didefinisikan dalam satuan pixel secara default.
- `align` berfungsi untuk mengatur perataan teks pada suatu tabel.Nilai atribut yang di berikan yaitu `left` (kiri) perataan teks ke kiri,`right` (kanan) untuk perataan teks ke kanan,dan untuk perataan teks ketengah menggunakan `center`.


**Contoh Program**

```html
<table Border="2">
<tr>
<th rowspan="2">nama</th>
<th colspan="2">Asal institusi</th>
</tr>
<tr>
<th width="150">sekolah</th>
<th width="150">kampus</th>
</tr>
<tr>
  <td>Ibrahim Malommbasang</td>
  <td>SMKN 7 Makassar</td>
  <td>Universitas Negeri Makassar</td>
</tr>
<tr>
  <td>Condrado Alain Sharon</td>
  <td rowspan="2"> SMKN 7 Makassar</td>
  <td align="center" rowspan="2">-</td>
</tr>
<tr>
  <td>Rezeky Awalya</td>
</tr>
  <td>Muzhawir Amri</td>
  <td>SMAN 1 Palu</td>
  <td>STMTK Dipanegara</td>
</tr>
</table>
```

**Hasil program Tabel yang menggunakan colspan & rowspan**:





>[!INFO] perhatikan pada konten elemen `<td` yang berisi `Rezeky Awalya`, hanya terdapat satu elemen `<td>` disana. Hal ini dikarenakan konten elemen `<td>` sebelumnya yaitu `SMKN 7 Makassar` dan `-` pada data `fatur` mengandung atribut `rowspan` dengan bernilai `2` yang secara otomatis mengisi data di bawahnya yakni data `Rezeky awalya`. Nilai `2` menunjukkan bahwa ada dua baris yang digabungkan menjadi satu.
>  Konsep ini juga sama dengan apa yang terjadi pada `<th rowspan="2">nama</th>` dan `<th colspan="2">Asal institusi</th>`


### Tabel Tugas Hari & Bulan

**Kode program**
```html
<table Border="5">
  <tr>
  <th bgcolor="green" colspan="2">Nama hari</th>
  <th bgcolor="green"colspan="2">Nama bulan</th>
  </tr>
  <tr>
    <td>Senin</td>
    <td>Selasa</td>
    <td>april</td>
  <td align="center" rowspan="2">Juli</td>
    </tr>
    <tr>
    <td>Rabu</td>
    <td>Kamis</td>
    <td>mei</td>
    </tr>
</table>
```

**Hasil tabel hari & bulan**:

![Gambar_0](Assets/IMG_0.jpg)

**Analisis**:
- `<table Border="5">`:Adalah untuk menentukan tebal dari Border tabelnya.
`<tr>`: Berfungsi untuk membuat kolom baris di tabel.
`<th bgcolor="red" colspan="2">Nama hari</th>`: `<th>` sebagai **tabel border**,`bg color` untuk menambah warna pada tabel,`colspan="2"` berupa tambahan baris tabel (samping),`nama hari` berupa nama untuk di bagian headernya dan diakhiri dengan tag`</th>.`
- `<td>Senin</td>`:`<td>` untuk membuat teks pada tabel.senin adalah isi teks dari tag `<td>` dan diakhiri dengan `</td>`.
- `<td align="center" rowspan="2">juli</td>`: diawali Dengan tag `<td` untuk menambahkan teks pada baris tabel.`align="center"` adalah untuk perataan teks dan menggunakan center untuk perataan tengah.`rowspan="2"` untuk menghubungkan baris kolom(kebawah) dan ditutup dengan tag`</td>`.
- `</tr>` menutup kolom baris pada tabel.
- `<tr>` menambah kolom baris pada tabel.
- `<td>Rabu</td> <td>Kamis</td> <td>mei</td>` isi dari tag `<Tr>`,`<td> `membuat teks pada tabel "Rabu Kamis mei" adalah isi dari tag `<td>` ditutup dengan tag`</td>`.
- `</table>` untuk mengakhiri tabel.



## **Form**


Elemen `<form>` HTML digunakan untuk mendefinisikan form yang digunakan untuk mengumpulkan inputan dari pengguna website. Tag ini digunakan untuk mengkoleksi inputan dari user, konsep ini sama seperti konsep formulir di dunia nyata.

>[!INFO]- Dengan kata lain tag `<fores> `merepresentasikan sebuah formulir di mana satu formulir bisa memiliki banyak kolom isian.



Form HTML berisikan elemen-elemen `form` lainnya. Elemen `<form>` digunakan untuk menampung macam-macam elemen yang berkaitan dengan sebuah `form`, seperti `text` `fields`, `checkbox`, `radio button`, tombol `submit`, dan banyak lagi yang dapat diedit kemudian ditulis untuk dikirim pada sebuah server untuk selanjutnya diproses guna mendapatkan informasi tertentu dari atau untuk user.

Umumnya, sebuah website selalu memiliki fitur form, contoh paling umum yang sering kita temui adalah seperti form login, form sign up, form komentar di suatu blog/media.

### **Input**

Elemen `<input>` adalah elemen form yang paling penting. Elemen `<input>` dapat ditampilkan dalam beberapa cara, tergantung pada nilai atribut `type` yang digunakan. Request Berikut adalah beberapa contoh nilai dari atribut `type`:
- **Text** digunakan untuk mengambil isian berupa **teks**.contohnya seperti nama.
- **password** digunakan untuk mengambil isian berupa **kata sandi** atau sesuatu yang bersifat rahasia.Tipe ini akan mengubah semua karakter yang diketikkan ke dalam karakter bulat.
- **radio** digunakan sebagai kolom isian bertipe `pilihan` yang menawarkan beberapa opsi kepada user namun tetapi **hanya satu opsi saja** yang boleh dipilih.contohnya seperti jenis kelamin atau agama.

>[!INFO]- Perlu diperhatikan bahwa untuk penggunaan tipe `radio`yang berkategori set pilihan yang sama mengharuskan nilai-nya juga sama.



Opsi default dapat dilakukan dengan menambahkan atribut checked pada elemen opsi yang dijadikan sebagai opsi default.

- **checkbox** digunakan untuk memberikan daftar pilihan dalam satu set opsi. User dapat memilih satu atau bahkan lebih dari satu pilihan pada tipe ini. Hal ini berbeda dengan tipe sebelumnya yaitu `radio` yang hanya memungkinkan user untuk memilih satu  pilihan saja. Contoh penggunaan `checkbox` seperti daftar makanan kesukaan, daftar olahraga yang tidak disukai, dan yang semisalnya.

>[!INFO]- Perlu diperhatikan bahwa untuk penggunaan tipe `checkbox` yang berkategori set pilihan yang sama mengharuskan nilai `name` -nya juga sama.



- **Number** digunakan untuk membatasi isian user hanya pada karakter numerik saja. Browser akan menambahkan dua buah tombol atas dan bawah untuk mengubah angka isian.

Beberapa atribut untuk tipe `number`:
- **min**-menentukan angka minimal
- **Max**-menentukan angka maksimal
- **step**-menentukan kelipatan (nilai yang tidak sesuai kelipatan tidak bisa di-input, dan default dari atribut ini adalah 1)

- **Date** digunakan untuk memberikan isian berupa tanggal. Atribut `min` dan `max` dapat pula difungsikan pada tipe ini untuk mengatur tanggal minimal dan tanggal maksimal yang diinginkan. Nilai `min` dan `max` tersebut ditulis dengan format: `YYYY-em-dd`.

- **File** digunakan untuk memungkinkan pengguna memuat file. Atribut `accept` juga dapat disisipkan pada tipe ini dengan maksud untuk mengatur file apa saja yang boleh di-upload. Beberapa contoh value dari atribut `accept` yaitu:

- `accept-"image/png,inage/jpg.Image/jpeg` - untuk file gambar seperti `png`. `jpg`. atau `jpeg`
- `accept="pdf"` - untuk file pdf
- `accept="pdf"` - untuk file pdf
- `accept-".doc, docx"` - untuk file `doc` atau `docx`
- `accept-".ppt, pptx"` untuk file `ppt` atau `pptx`

- **submit** ditampilkan dalam bentuk tombol untuk mengirim data pada `<form>` yang menjadi pembungkusnya. Atribut `value` digunakan untuk mengisi teks yang ingin ditampilkan pada tombol.

- **reset** berguna untuk **mengembalikan state (keadaan) atau data dari suatu form ke nilai awalnya**. Jika nilai awal sebuah input adalah kosong, maka ketika direset ia akan kembali kosong. Tapi jika nilai awalnya sudah terisi sesuatu, maka ketika direset datanya akan kembali seperti yang sudah diset sebelumnya.

- **button** berguna untuk membuat inputan berupa sebuah tombol. Tombol ini nantinya bisa difungsikan sesuai dengan keinginan dari pengembang web.

### *Label*
Elemen `<label>` memiliki fungsi khusus untuk melabeli sebuah kolom inputan. Ketika screen reader membaca konten halaman HTML, lalu menemukan sebuah inputan, ia akan membaca label yang bersangkutan. 
Fungsi lain dari tag `<label>` adalah ketika kita mengklik label, maka browser akan meletakkan fokus pada kolom isian yang terhubung dengannya. Syarat yang perlu diperhatikan yaitu dengan menghubungkan sebuah `<label>` dan `<input>` dengan atribut for untuk label, dan atribut id pada `<input>` dengan nilai untuk kedua atribut tersebut mesti sama persis.

### *Select*
Elemen `<select>` berguna dalam mendefinisikan sebuah tombol dropdown yang dimana user dapat memilih salah satu dari banyak pilihan.

>[!note] - Elemen `<select>` nantinya berperan sebagai kontainer atau pembungkus dari elemen `<option>` yang berperan sebagai daftar pilihan atau opsi. 

 Elemen `<select>` hampir mirip fungsinya dengan `<input type ="radio">` akan tetapi baiknya elemen `<select>` digunakan untuk memilih satu pilihan yang terdapat banyak opsi di dalamnya, sedangkan `<input type ="radio">` lebih baiknya untuk digunakan jika user diarahkan memilih hanya satu pilihan yang opsi pilihannya tidak terlalu banyak. Contoh penggunaan elemen ini seperti memasukkan pilihan berupa asal daerah atau yang semisalnya.
Penting untuk diketahui bahwasanya opsi yang aktif secara default adalah adalah opsi yang pertama. Akan tetapi, kita bisa mengatur opsi mana yang aktif secara default dengan menambahkan atribut selected pada suatu `<option>` yang ingin dijadikan sebagai opsi default.

### *Text Area*
Elemen `<textarea>` berguna untuk mengambil inputan user berupa teks yang dapat memuat lebih dari satu baris. Jika dibandingkan dengan elemen `<input>` teks biasa, elemen `<textarea>` memiliki ukuran tinggi yang lebih besar. Element `<textarea>` bisa diisi lebih dari satu baris dengan menekan enter.

Atribut yang dapat digunakan untuk mengatur kuran dari textarea yaitu rows untuk jumlah baris, sedangkan atribut cols untuk lebarnya.

### *Button*
Elemen `<button>` yang berada di dalam sebuah `form` akan otomatis dianggap sama fungsinya seperti `<input type="submit">`. Jika ingin membuat tombol biasa yang tidak men-submit `<form>` dapat dilakukan dengan menambahkan atribut `type="button"`.

contoh : 
```html
<h1>Formulir Pendaftaran</h1>
<form action="">
  <div>
    <label for="nama-lengkap"><b>Nama Lengkap:</b></label
    ><br />
    <input
      type="text"
      id="nama-lengkap"
      name="nama_lengkap"
      placeholder="Masukkan nama lengkap"
      required
    />
  </div>
  
  <div>
    <label for="password"><b>Password:</b></label
    ><br />
    <input
      type="password"
      id="password"
      name="password"
      placeholder="Masukkan password"
      required
    />
  </div>
  
  <div>
    <b>Jenis Kelamin:</b><br />
    <input id="lk" type="radio" name="jenis_kelamin" checked />
    <label for="lk">Laki-Laki</label>
    <input id="pr" type="radio" name="jenis_kelamin" />
    <label for="pr">Perempuan</label>
  </div>
  
  <div>
    <label for="isian-usia"><b>Usia:</b></label
    ><br />
    <input
      type="number"
      id="isian-usia"
      name="usia"
      min="17"
      max="25"
      value="19"
      required
    />
    Tahun
  </div>

  <div>
    <label for="tgl-ijazah"><b>Tanggal Ijazah:</b></label> <br />
    <input
      type="date"
      id="tgl-ijazah"
      name="tgl_ijazah"
      min="2021-01-01"
      value="2023-06-20"
      required
    />
  </div>

  <div>
    <label for="opsi-agama"><b>Agama:</b></label
    ><br />
    <select id="opsi-agama" name="agama" required>
      <option disabled>---Pilih Agama----</option>
      <option value="islam">Islam</option>
      <option value="kristen">Kristen</option>
      <option value="katolik">Katolik</option>
      <option value="hindu">Hindu</option>
      <option value="buddha">Buddha</option>
      <option value="atheis" disabled>Atheis</option>
    </select>
  </div>

  <div>
    <label for="alamat"><b>Alamat:</b></label> <br />
    <textarea
      id="alamat"
      name="alamat"
      cols="25"
      rows="5"
      placeholder="Harap masukkan alamat secara lengkap"
      required
    ></textarea>
  </div>

  <div>
    <b>Kemampuan Berbahasa Asing:*</b><br />
    <input type="checkbox" id="inggris" name="bahasa_asing" />
    <label for="inggris">Inggris</label>
    <input type="checkbox" id="arab" name="bahasa_asing" />
    <label for="arab">Arab</label>
    <input type="checkbox" id="jepang" name="bahasa_asing" />
    <label for="jepang">Jepang</label>
  </div>

  <div>
    <label for="isian-foto"><b>Foto 4x6:*</b></label
    ><br />
    <input
      type="file"
      id="isian-foto"
      name="foto"
      accept="image/png,image/jpg,image/jpeg"
    />
  </div>

  <br />
  <input type="submit" value="Kirim" />
  <input type="reset" value="Batal" />
  <i>*opsional (tidak wajib diisi)</i>
</form>
```


**Hasil Formulir pendaftaran**:

![Gambar_22](Assets/IMG_22.jpg)



Beberapa atribut yang digunakan pada contoh di atas yang perlu untuk diperjelas yaitu sebagai berikut:
- **name** - digunakan sebagai nama variabel yang akan diproses oleh web server (contoh menggunakan PHP).
- **required** - digunakan untuk memastikan bahwa pengguna harus memasukkan nilai pada input tersebut sebelum dapat melakukan proses submit formulir.
- **placeholder** - menuliskan teks pada elemen input. Placeholder sangat bermanfaat untuk memberikan teks bantuan kepada user untuk inputan form yang kompleks.
- **value** - menentukan nilai awal dari sebuah elemen input.
- **disabled** - digunakan untuk menonaktifkan inputan pada elemen yang diberi atribut ini.


### **Bagaimana Cara Memproses Form?**

Ketika sebuah `<form>` disubmit, baik menggunakan elemen `<button>` mau pun `<input type="submit">`, browser akan mengirimkan data tersebut kepada URL yang didefinisikan pada atribut `action` di dalam tag `form`.

Ada pun jika atribut `action` tidak didefinisikan, maka *browser* akan menggunakan URL sekarang sebagai tujuan pengiriman data.

**Contoh**:

```html
**<form** action**=**"/proses-pendaftaran"**>**
  ...
**</form>**
```


Pada contoh di atas, ketika form di-*submit*, *browser* akan mengirimkan data yang ada  menuju URL `/proses-pendaftaran`.


**Apa yang terjadi pada URL `/proses-pendaftaran`?**

Pada URL tersebut terdapat sebuah aplikasi/program yang berjalan di *server* (bukan di *browser*). Tugas dari program tersebut adalah mengelola data yang dikirim seperti misalnya menyimpan data tersebut ke dalam sebuah *database*.

Bahasa yang umum digunakan di dalam server adalah **python**, **nodejs**, **PHP**, dan lain sebagainya.

Untuk mendapatkan gambaran lebih jelas, sebenarnya akan dijelaskan pada modul selanjutnya yang berkaitan dengan materi PHP atau juga bisa dengan membaca tutorial berikut:

https://jagongoding.com/web/php/web-dinamis/membuat-dan-menangani-form/

### **Form Latihan**

**Kode program**:

```html
<form>
  <label for="nama">nama: </label>
  <input type="text" id="nama">
  <br>
<br>
<label for="password"> password:</label>
  <input type="text" id="password"required>
  <br>
  <br>
  <label for="jenis kelamin">jenis kelamin</label>
  <input type="radio" name="jenis kelamin" checked>
  <label>LakiLaki</label>
  <input type="radio" name="jenis kelamin">
  <label>Perempuan</label>
  <br>
  <br>
  <input type="checkbox" name="bahasa">WEB
  <br>
  <br>
   <input type="checkbox" name="bahasa">MOBILE
  <br>
  <br>
 <input type="checkbox" name="bahasa">DEKSTOP
 <br>
 <br>
 Pesan Pesanan Anda:
 <br>
 <textarea>
 </textarea>
 <br>
 <br>
 <input type="submit" value="kirim">
<br>
<br>
 <input type="reset" value="ulang">
</form>
```
 

**Hasil program Form Latihan**:

![Gambar_FORM](Assets/IMG_FORM.jpg)
## DIV & SPAN

### Div

#### Penjelasan 

tag `<Div>` merupakan tag yang digunakan untuk membuat layer.

#### Contoh
```html
<div>ini dibuat menggunakan div</div>
<div>ini juga menggunakan div</div>
```

#### Hasil

![Gambar_div](Assets/div.jpg)


### Span

#### penjelasan

`<span>` adalah elemen HTML yang digunakan untuk mengelompokkan atau memberikan gaya pada sebagian teks atau elemen lainnya di dalam dokumen HTML.
#### Contoh
```html
<span>ini dibuat menggunakan span</span>
<span>ini juga menggunakan span</span>
```

#### Hasil

![Gambar_span](Assets/span.jpg)



