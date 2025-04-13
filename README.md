# TP6DPBO2025C2

# Janji
Saya Ahmad Izzuddin Azzam dengan NIM 2300492 berjanji mengerjakan TP6 DPBO dengan keberkahan-Nya, maka saya tidak akan melakukan kecurangan sesuai yang telah di spesifikasikan, Aamiin

# Flappy Bird Game

Flappy bird Pada modul ini, kita akan membuat ulang game yang dirilis tahun 2013, yaitu Flappy Bird, dengan langkah - langkah untuk membuat Flappy Bird menggunakan Java Swing GUI sebagai berikut :

## Desain Program

Program ini terdiri dari beberapa komponen utama:
1. **Player (Burung)**: Objek player yang bergerak secara vertikal dan memiliki kecepatan (velocity) yang dipengaruhi oleh gravitasi.
2. **Pipe (Pipa)**: Dua pipa yang bergerak horizontal di layar. Pipa ini memiliki celah yang menjadi jalur aman bagi burung untuk melewatinya.
3. **Game Loop**: Timer yang menjalankan permainan pada kecepatan 60 FPS, melakukan update posisi burung, pipa, dan mendeteksi tabrakan.
4. **Suara**: Program ini memutar suara pada saat permainan dimulai, saat burung melewati pipa, dan saat game over.

### Komponen Utama:
- **`FlappyBird.java`**: Kelas utama yang menjalankan logika permainan.
- **`Player.java`**: Kelas untuk mengatur properti dan gerakan burung.
- **`Pipe.java`**: Kelas untuk mengatur posisi, gambar, dan logika pipa.
- **`Sounds`**: Folder yang berisi file suara untuk efek suara permainan.

## Alur Permainan

1. **Start Screen**: Ketika permainan dimulai, layar akan menunjukkan pesan "Welcome to Flappy Game!" dan tombol untuk memulai permainan dengan menekan `SPACE`.
2. **Permainan Dimulai**: Burung akan bergerak turun dan naik berdasarkan input pemain (menekan tombol `SPACE` untuk memberikan dorongan ke atas). Pipa akan muncul secara berkala dari kanan ke kiri.
3. **Tabrakan**: Jika burung bertabrakan dengan pipa atau jatuh ke bawah, permainan akan berakhir dan layar menampilkan pesan "Game Over" dengan skor.
4. **Restart Game**: Pemain dapat menekan tombol `R` untuk memulai permainan kembali setelah game over.

## Fitur
- **Suara**: Suara dimulai saat permainan dimulai dan berlanjut selama permainan.
- **Skor**: Skor bertambah setiap kali burung berhasil melewati celah antara pipa tanpa tabrakan.
- **Kontrol**: 
  - **`SPACE`**: Menekan tombol ini membuat burung terbang naik (memberikan dorongan).
  - **`R`**: Menekan tombol ini setelah permainan berakhir akan mereset permainan.

## Dokumentasi Saat Program Dijalankan

1. **Layar Start**: Ketika program pertama kali dijalankan, akan muncul layar selamat datang dengan tulisan "Press SPACE to start".
   
![Screenshot 2025-04-13 214257](https://github.com/user-attachments/assets/c21248b5-84d2-4115-b521-3dd24c43a785)


2. **Permainan Berjalan**: Setelah menekan `SPACE`, permainan dimulai. Burung mulai bergerak ke bawah dan bisa melompat ketika tombol `SPACE` ditekan. Pipa muncul dari sisi kanan layar.

![Screenshot 2025-04-13 214903](https://github.com/user-attachments/assets/e4bd1399-643b-4591-82d3-cd21f4520ab6)


3. **Game Over**: Jika burung menabrak pipa atau jatuh ke tanah, permainan berakhir dan layar menampilkan skor terakhir serta tombol untuk restart dengan menekan `R`.

![Screenshot 2025-04-13 214250](https://github.com/user-attachments/assets/90ca3e51-612f-490c-ab16-79701c9814f2)

## Cara Menjalankan Program

1. **Prasyarat**:
   - Java 8 atau versi lebih tinggi terinstal di sistem Anda.
   
2. **Menjalankan Program**:
   - Pastikan semua file sumber daya (gambar dan suara) sudah ada di dalam folder yang sesuai.
   - Buka terminal atau command prompt dan navigasikan ke direktori yang berisi file `FlappyBird.java`.
   - Jalankan perintah berikut untuk mengompilasi dan menjalankan program:
   
     ```
     javac FlappyBird.java
     java FlappyBird
     ```

3. **Tombol Permainan**:
   - **`SPACE`**: Mengendalikan burung untuk terbang.
   - **`R`**: Untuk memulai ulang permainan setelah Game Over.
