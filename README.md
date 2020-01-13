# Pembangunan Korpus dan Model Relasi Semantik Hiponim-Hipernim Bahasa Indonesia dengan Pendekatan Pattern-Based, Crowdsourcing, dan Machine Learning

Pekerjaan ini merupakan Tugas Akhir/Skripsi dari Yudhistira Erlandinata, mahasiswa Fakultas Ilmu Komputer Universitas Indonesia angkatan 2016.
Dibimbing oleh Bapak Rahmad Mahendra, S.Kom., M.Sc.

## Kandidat Korpus Crowdsourcing
```korpus_crowdsourcing_kandidat.txt```

Dihasilkan dengan metode pattern-based dan memenuhi dua syarat berikut.
- pasangan kata yang kedua katanya terdapat pada KBBI V atau dideteksi sebagai MWE oleh POS Tagger Rashel et al (2014)
- pasangan kata yang memiliki nilai PPMI > 0. PPMI dihitung berdasarkan kemunculan pada korpus kalimat Wikipedia.

## Korpus Crowdsourcing
```korpus_crowdsourcing.txt```

Beberapa hal penting perlu diketahui sebelum menggunakan korpus
- korpus dibangun dengan teknik crowdsourcing
- jumlah anotator untuk setiap entri pada korpus adalah 5
- entri ke-i dan entri ke-j pada korpus dianotasi oleh dua kelompok anotator yang berbeda karena anotator crowdsourcing tidak diwajibkan menyelesaikan semua tugas anotasi
- nilai kappa nya adalah 0.37 (fair agreement), dihitung dengan metode Free-Marginal Multirater Kappa

## Gold Standard Gamifikasi
```gold_standard_gamifikasi.txt```

Dibuat untuk quality control anotasi crowdsourcing. Dibuat oleh satu anotator.

