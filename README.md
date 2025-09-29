Nama : Zahrah Amanda Fauziyah
Kelas : TI.24.A.2
NIM : 312410193

    Pertanyaan dan Tugas :
    
    1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
    dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
    2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
    penjelasannya!
    3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
    elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
    penjelasan dan contohnya!
    4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
    terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
    Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )

    Jawaban :
1. <img width="1920" height="1080" alt="Cuplikan layar 2025-09-29 134551" src="https://github.com/user-attachments/assets/0b99618e-3377-4af6-851b-b06785c42140" />
Penjelasan : Gambar 1
- Tampilan masih default HTML dengan sedikit CSS.
- Heading <h1> dan teks belum diberi warna atau dekorasi.
- Link masih bergaya standar browser (biru & underline).
- Menunjukkan kondisi awal sebelum banyak styling CSS ditambahkan.
  
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-29 134713" src="https://github.com/user-attachments/assets/1681b705-f430-4845-b6f8-266a06437788" />
Penjelasan : Gambar 2
- Judul utama berubah posisi menjadi center dan diberi efek font-style: italic pada kata Inline CSS.
- Link navigasi di atas sudah berubah warna menjadi biru terang dengan underline.
- Heading "Hello World" sudah diberi warna biru tua dan bold.
- CSS internal sudah mulai dipakai untuk mempercantik teks.
  
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-29 135207" src="https://github.com/user-attachments/assets/bae58adf-8fc1-489d-a401-a16c9c30b280" />
Penjelasan : Gambar 3
- Background halaman mulai diberi warna abu-abu muda (lightgray).
- Teks paragraf di bawah "Hello World" menjadi pudar (abu tipis) dengan color: lightgray;.
- Efek CSS lebih jelas, menunjukkan perbedaan teks utama dan teks pendukung.
  
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-29 140039" src="https://github.com/user-attachments/assets/e3a440cb-68ba-4bfc-96e1-3e43c104d9da" />
Pnjelasan : Gambar 4
- Navigasi berubah menjadi bar hijau horizontal dengan tulisan putih.
- Heading "Hello World" tetap biru.
- Paragraf masih abu tipis.
- Mulai terlihat struktur layout website modern dengan navigasi atas.
  
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-29 140248" src="https://github.com/user-attachments/assets/44b538df-2e4e-43e4-9d28-d126f861b159" />
Penjelasan : Gambar 5
- Bagian konten utama diberi background biru tua.
- Teks paragraf berwarna putih agar kontras dengan background.
- Tombol/link “Informasi selengkapnya” menjadi merah mencolok dengan padding.
- CSS di sini sudah mengarah ke desain UI/UX modern (kontras warna & tombol jelas).
  
<img width="1920" height="1080" alt="Cuplikan layar 2025-09-29 140639" src="https://github.com/user-attachments/assets/5dfe4564-d4c4-4b16-b699-31d756e94631" />
Penjelasan : Gambar 6
- Navigasi berubah menjadi hijau muda, area konten menjadi pink terang.
- Heading "Hello World" berwarna putih.
- Tombol “Informasi selengkapnya” berubah jadi hijau muda.
- Eksperimen dengan kombinasi warna berbeda untuk menguji estetika tampilan.

        2. - h1 { ... } → mengatur semua elemen <h1> di halaman (global).
        - #intro h1 { ... } → hanya mengatur elemen <h1> yang berada di dalam elemen dengan id="intro" (spesifik).
        - Jadi perbedaannya ada pada cakupan: h1 berlaku umum, sedangkan #intro h1 hanya berlaku pada bagian tertentu saja.

        3. - Jika ada eksternal, internal, dan inline CSS pada elemen yang sama:
        - Inline CSS akan ditampilkan (paling kuat).
        - Jika tidak ada inline, maka internal CSS dipakai.
        - Kalau tidak ada internal, maka eksternal CSS dipakai.
        - Urutan prioritas: Inline > Internal > Eksternal.

        4. - Jika sebuah elemen punya ID dan class, keduanya punya aturan CSS berbeda, maka browser memilih berdasarkan tingkat specificity. Selector ID (#id) memiliki bobot lebih tinggi (100) dibanding class (.class) (10), sehingga deklarasi ID menang dan ditampilkan.
       - Urutan kekuatan: inline (1000) > #id (100) > .class (10) > elemen (1).
