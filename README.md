# Aho-Corasick Text Finder
> Task Seleksi Lab IRK created by William,
versi **1 Agustus 2024**

## 💡 Latar Belakang
Dalam tugas besar ini, Anda diminta untuk mengimplementasikan algoritma Aho-Corasick untuk mencari suatu set string dari query teks tertentu.

Secara besar, algoritma ini akan membangun automaton berbasis trie dan state machine secara offline. Automaton yang telah dibuat secara offline ini akan bermanfaat ketika melakukan pencarian teks online nantinya, karena tidak perlu melakukan perbandingan indeks satu per satu lagi. Penerapan algoritma ini biasanya dilakukan ketika terdapat sekumpulan database string target yang telah diketahui, misalnya DB sekuens DNA penyakit tertentu, atau database kode binary dari virus.

## 📝 Spesifikasi Tugas
### Fitur Wajib (1750 poin)
1. **Implementasi Algoritma Aho-Corasick: (1250 poin)**
   - Cari dan cocokkan beberapa pola dari query string dalam teks.
   - Hitung dan tampilkan jumlah kemunculan setiap pola dalam teks.
   - Pencarian string diasumsikan case-insensitive.

2. **Input Program:**
   - Terima set string target dan teks query dari file .json:
     ```json
     {
       "text": "saya sangat suka matkul irk. saya jadi ingin makan ayam.",
       "patterns": ["saya", "ayam", "aman"]
     }
     ```

3. **Output Program:**
   - Tampilkan banyak kemunculan setiap string target dalam teks. Contoh:
     ```
     Pola "saya" ditemukan 2x.
     Pola "ayam" ditemukan 1x.
     Pola "aman" ditemukan 0x.
     ```

4. **GUI & Bahasa Pemrograman: (500 poin)**
   - Buat GUI sederhana untuk operasi fitur wajib.
   - Tidak ada batasan bahasa pemrograman.

### Fitur Bonus (1000 poin)
1. **Highlight Indeks Pola yang Ditemukan: (500 poin)**
   - Tandai indeks dalam teks di mana pola ditemukan. Contoh:
     ```
     Pola "saya" ditemukan 1x, ditemukan pada indeks [(0,3)]
     ```

2. **Visualisasi Automaton: (500 poin)**
   - Visualisasikan automaton yang terbentuk.
<div align=center>
<img  src="https://github.com/user-attachments/assets/ccc9feed-e991-49de-90a3-6aee56c3b821">
</div>

## 📂 Pengerjaan dan Pengumpulan
- Pengumpulan dilakukan pada webapp seleksi.
- Buat README untuk dokumentasi yang minimal mencakup cara menjalankan program, dan output hasil uji setiap fitur dari program.
- Repo private, invite `williamnixon20`.
- Hubungi untuk demo aplikasi maksimal H+1 setelah pengumpulan. Hubungi id line: (https://line.me/ti/p/-_bBNAlIOI) untuk menjadwalkan demo aplikasi (wajib untuk dinilai).

## 📌 Penilaian
| Tipe | Aspek | Nilai Maksimum |
|------|-------|----------------|
| Fitur Wajib | Algoritma | 750 |
| Fitur Wajib | Kebenaran Program | 500 |
| Fitur Wajib | GUI | 500 |
| Bonus | Highlighting Teks | 500 |
| Bonus | Visualisasi Automaton | 500 |
| **Total Maksimum** | | **2250** |

## Lain-lain
Link google docs spesifikasi: https://docs.google.com/document/d/1Gg7zbre1MScbmMALHUAtucYzIwLhuyxsC6t2YDQ5I9c/edit
