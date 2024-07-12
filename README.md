# Aho-Corasick Algorithm

## Tugas Kecil Seleksi Lab Ilmu Rekayasa dan Komputasi

### Aho-Corasick Text Finder

#### Deskripsi Tugas
Implementasikan algoritma Aho-Corasick untuk mencari sekumpulan string dari query teks tertentu. Algoritma ini membangun automaton berbasis trie dan state machine secara offline untuk pencarian teks.

#### Fitur Wajib
1. **Implementasi Algoritma Aho-Corasick:**
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

4. **GUI & Bahasa Pemrograman:**
   - Buat GUI sederhana untuk operasi fitur wajib.
   - Tidak ada batasan bahasa pemrograman.

#### Bonus
1. **Highlight Indeks Pola yang Ditemukan:**
   - Tandai indeks dalam teks di mana pola ditemukan. Contoh:
     ```
     Pola "saya" ditemukan 1x, ditemukan pada indeks [(0,3)]
     ```

2. **Visualisasi Automaton:**
   - Visualisasikan automaton yang terbentuk.

#### Pengumpulan
- Pengumpulan dilakukan pada webapp seleksi.
- Buat README untuk dokumentasi pengembangan.
- Repo private, invite `williamnixon20`.
- Hubungi untuk demo aplikasi maksimal H+1 setelah pengumpulan.

#### Penilaian
| Tipe | Aspek | Nilai Maksimum |
|------|-------|----------------|
| Fitur Wajib | Algoritma | 750 |
| Fitur Wajib | Kebenaran Program | 500 |
| Fitur Wajib | GUI | 500 |
| Bonus | Highlighting Teks | 500 |
| Bonus | Visualisasi Automaton | 500 |
| **Total Maksimum** | | **2250** |

#### Misc
Link google docs spesifikasi: https://docs.google.com/document/d/1Gg7zbre1MScbmMALHUAtucYzIwLhuyxsC6t2YDQ5I9c/edit
