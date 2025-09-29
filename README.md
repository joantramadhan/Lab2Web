1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
 
 before : <br>
<img width="552" height="765" alt="Tag HTML dasar - portofolio - Visual Studio Code 29_09_2025 13 50 41" src="https://github.com/user-attachments/assets/45e4ffc8-e4d4-4780-86a1-e3ad569dfabf" /><br>
after:<br>
<img width="923" height="893" alt="● h1 { • Untitled-1 - portofolio - Visual Studio Code 29_09_2025 13 32 47" src="https://github.com/user-attachments/assets/106ab275-07a1-42c5-9f5a-42a1da5bc4d7" /><br>


 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!<br>
   jawaban : h1{...} sebagai selector global untuk semua elemen tag h1 yang ada di halaman
    #intro h1 {...} selector kusus yg cuma berlaku untuk tag h1 yang ada di dalam elemn dengan id="intro"


 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
    jawaban : inline yang akan di tampilkan lebih dahulu di browser karna lebih di prioritaskan, dan juga karna berada di dalam elemen



 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

    <br> jawaban : yang akan di tampilkan adalah ID karna ID lebih spesifik dan punya bobot lebih ketimbang class yang hasilnya menampilkan textnya berwarna merah
    
------------------------------------------------------
1. Membuat dokumen HTML<br>
membuat kerangka dokumen seperti foto di bawah<br>
<img width="1920" height="1128" alt="● _!DOCTYPE html_ • Untitled-1 - portofolio - Visual Studio Code 29_09_2025 14 47 07" src="https://github.com/user-attachments/assets/0f26dab5-ef3e-46f5-859c-a45c6867f592" />

2. Mendeklarasikan CSS Internal<br>
Kemudian menambahkan deklarasi CSS internal seperti foto di bawah pada bagian head dokumen.<br>
<img width="1920" height="1128" alt="● _!DOCTYPE html_ • Untitled-1 - portofolio - Visual Studio Code 29_09_2025 14 47 25" src="https://github.com/user-attachments/assets/f02abd1f-748f-4b7c-8823-96610bfb3fd5" />

3. Menambahkan Inline CSS<br>
   deklarasikan inline CSS pada tag <p> seperti berikut.<br>
<img width="1920" height="1128" alt="● _!DOCTYPE html_ • Untitled-1 - portofolio - Visual Studio Code 29_09_2025 14 55 24" src="https://github.com/user-attachments/assets/a018e122-4ef3-4026-a762-66f7c7005199" />
4. Membuat CSS Eksternal<br>
<img width="1920" height="1128" alt="Lab2web html - portofolio - Visual Studio Code 29_09_2025 15 04 04" src="https://github.com/user-attachments/assets/dae2d9a3-f6b5-4946-a466-e0877069fe0c" />
5. Menambahkan CSS Selector<br>
menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
style_eksternal.css.<br>
<img width="1920" height="1128" alt="Lab2web html - portofolio - Visual Studio Code 29_09_2025 15 04 46" src="https://github.com/user-attachments/assets/55fefedc-7572-4571-b662-074a70654c49" />
