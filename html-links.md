# HTML LINKS

Anda dapat mengklik tautan dan melompat ke dokumen lain. Saat Anda menggerakkan mouse di atas tautan, panah mouse akan berubah menjadi tangan kecil. 

```Catatan: Tautan tidak harus berupa teks. Tautan dapat berupa gambar atau elemen HTML lainnya!```

### syntax
Tag HTML ```<a>``` mendefinisikan <i>hyperlink</>
<i>Syntax</i> sebagai berikut:
```
<a href="url">link</a>
```
Atribut terpenting dari tag ```<a>``` adalah ```href``` yang menunjukkan tujuan tautan. Teks tautan adalah bagian yang akan terlihat oleh pembaca.
Mengklik teks tautan, akan mengirim pembaca ke alamat URL yang ditentukan.

Contoh :
```
<a href="https://google.com/">Google</a>
```
dengan hasil seperti berikut

<a href="https://google.com/">Google</a>

Secara <i>default</i>, link (tautan) akan ditampilkan pada semua browser sebagai berikut :
- Tautan yang belum dikunjungi digarisbawahi dan berwarna biru
- Tautan yang dikunjungi digarisbawahi dan berwarna ungu
- Tautan aktif digarisbawahi dan merah

Tip: Tautan tentu saja dapat ditata dengan CSS, untuk mendapatkan tampilan lain!

### Atribut Target
Secara default, halaman tertaut akan ditampilkan di jendela browser saat ini. Untuk mengubahnya, Anda harus menentukan target lain untuk tautan tersebut.

Atribut ```target``` menentukan tempat untuk membuka dokumen tertaut. 
Atribut ```target``` dapat memiliki salah satu dari nilai berikut:
- ```_self``` - Bawaan. Membuka dokumen di jendela/tab yang sama dengan yang diklik
- ```_blank``` - Membuka dokumen di jendela atau tab baru
- ```_parent``` - Membuka dokumen dalam bingkai induk
- ```_top``` - Membuka dokumen di seluruh badan jendela

Contoh :
```<a href="https://www.google.com/" target="_blank">Kunjungi Google!</a>```

dengan hasil :

<a href="https://www.google.com/" target="_blank">Kunjungi Google!</a>

### Foto sebagai tautan
Untuk menggunakan gambar sebagai tautan, cukup letakkan tag ```<img>``` di dalam tag ```<a>```

Contoh:
```
<a href="https://www.google.com/">
<img src="https://www.designbust.com/download/1016/png/google_logo_png_transparent512.png" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```

dengan hasil :

<a href="https://www.google.com/">
<img src="https://www.designbust.com/download/1016/png/google_logo_png_transparent512.png" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

### Tautan Email
Gunakan ```mailto:``` di dalam atribut href untuk membuat tautan yang membuka program email pengguna (agar mereka dapat mengirim email baru):

Contoh :
```
<a href="mailto:fariszakyalfaiz@outlook.co.id">Kirim email</a>
```

dengan hasil :

<a href="mailto:fariszakyalfaiz@outlook.co.id">Kirim email</a>

Latihan!

Buatlah halaman HTML berisi biodata dengan ketentuan :
- title - Biodata
- heading 2 - Biodata
- table :
    - 2 kolom
    - baris berisi (nama, ttl, alamat, hobi, email, sosial media (fb, twitter, ig)
    - buat <i>hyperlink</i> atau tautan pada masing-masing media sosial
        - email
        - fb : target default
        - twitter : target top
        - ig : target blank, gunakan image link menggunakan logo ig
    - gunakan unordered list pada daftar media sosial
