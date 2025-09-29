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

    <br> jawaban : ID lebih spesifik dan punya bobot lebih ketimbang class yang hasilnya menampilkan textnya berwarna merah
    <br> contoh bisa di gabung dengan css ini : <br>#paragraf-1 { color: red; }   
.text-paragraf { color: blue; }

