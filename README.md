*Membuat Repository*
1. Login Github lalu buat Repository dengan judul Lab1Web
![1.png](img/1.png)

2. Clone URL Github Lab1Web
![2.png](img/2.png)
![3.png](img/3.png)

Setelah Clone maka di dalam folder Lab1Web terdapat file README 
![4.png](img/4.png)

*Membuat Web Dasar*
1. Buka Text editor (Text editor yang saya gunakan yaitu Visual Studio Code) 
2. Lalu pilih File pilih Open folder, dan buka folder yang di clone Tadi.
![5.png](img/5.png)
3. Maka Folder Lab1Web Terbuka
![6.png](img/6.png)
4. Lalu buat file baru dengan nama `lab1_tag_dasar.html`
![7.png](img/7.png)
5. dan buatlah Struktur HTML dan `lab1_tag_dasar.html`
![8.png](img/8.png)
6. Lalu buka Live Preview atau atau Jaringan Localhost di Browser
![9.png](img/9.png)
7. Ubah titel menjadi Tag HTML dasar
![10.png](img/10.png)
![11.png](img/11.png) 
8. Membuat 2 Paragraf menggunkan tag <p></p>
![12.png](img/12.png)
Maka Tampilannya Sebagai Berikut
![13.png](img/13.png)
9. Kemudian mengatur atribut paragraf dengan menggunakan atribut align-center dan right
![14.png](img/14.png)
Dan tampilannya
![15.png](img/15.png)
10. Membuat judul halaman dengan tag h1 dan h2 dengan mengubah tampilan font
![16.png](img/16.png)
Lalu tampilannya
![17.png](img/17.png)
11. Menambahkan gambar pada dokumen menggunakan tag img
![18.png](img/18.png)
lalu tampilannya
![19.png](img/19.png)
12. Membuat link navigasi dengan menggunakan tag nav dan a
![20.png](img/20.png)
dan tampilan hyperlink 
![21.png](img/21.png)

*Lalu Push ke repository Github*
1. Buka gitbash di folder Lab1Wab
![22.png](img/22.png)
`git status -> untuk memeriksa apakah ada perubahan di repository`
`git add "nama file/folder" atau git add . -> untuk memasukan perubahan ke repository`
`git commit -m "pesan" -> untuk memberikan pesan atau deskripsi apa saja yang berubah`
`git push -> untuk mengirim file dari git bas ke github`
![23.png](img/23.png)
![24.png](img/24.png)
![25.png](img/25.png)
*Maka Folder tersebut sudah masuk di github*
![26.png](img/26.png)

**Jawab Pertanyaan Berikut**
`1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag? jika terjadi kesalahan penulisan tag maka tag tidak berfungsi`
`2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya! tag p membuat paragraf sedangkan tag br untuk membuat alenia baru`
`3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya! title img adalah atribut yang dapat ditambahkan ke tag gambar dalam HTML sedangkan ALT adalah atribut yang di tamabhkan ke tag gambar dalam HTML. tek ini muncul didalam wadah gambar ketika gambar tidak dapat di tampilkan. ini membantu mesin pencari memahami isi dari gambar tersebut.` 
`4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya! jika ingin gambar presisi dengan ukuran panjang dan lebar nya cukup dengan menggunakan atribut weidth saja karena atribut ini berfungsi mengatur lebar gambar secara keseluruhan. karena atribut height hanya dapat mengatur tinggi gambar saja.`
`5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut? blank digunakan untuk membuka windows baru. self digunakan apabila target frame adalah frame tempat link berada. top digunakan apabila target frame adalah windows tempat frame berada menggunkan top maka definisi frame yang ada apa windows browser akan hilang diganti dengan frame yang baru jika ada. parent digunaka apabila frame adalah setingkat dengan frame link berada akibat dari target frame akan dsama jika tempat frame link berada hanya satu level dibawah definisi frame windows.` 