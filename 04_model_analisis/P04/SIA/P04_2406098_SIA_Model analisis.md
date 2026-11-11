# Spesifikasi Hubungan Diagram Kumulatif SIA

| No. | Sumber | Hubungan | Tujuan |
|---|---|---|---|
| 1 | Civitas Akademika | Association | SIA-UC07 Lihat Kalender Akademik |
| 2 | Civitas Akademika | Association | Melihat Jadwal Kuliah |
| 3 | Mahasiswa | Generalization → | Civitas Akademika |
| 4 | Dosen | Generalization → | Civitas Akademika |
| 5 | Mahasiswa | Association | Mengajukan KRS |
| 6 | Mahasiswa | Association | SIA-UC09 Lihat KHS |
| 7 | Dosen | Association | SIA-UC08 Input Nilai Mata Kuliah |
| 8 | Admin Akademik | Association | SIA-UC10 Kelola Data Mahasiswa |
| 9 | Admin Akademik | Association | Kelola Jadwal Kuliah |
| 10 | Dosen Wali | Association | Menyetujui Keputusan KRS |
| 11 | Mengajukan KRS | «include» | Validasi KRS |
| 12 | Unduh Bukti Pengajuan KRS | «extend» | Mengajukan KRS |
| 13 | SIA-UC11 Tambah Data Mahasiswa | Generalization → | SIA-UC10 Kelola Data Mahasiswa |
| 14 | SIA-UC12 Ubah Data Mahasiswa | Generalization → | SIA-UC10 Kelola Data Mahasiswa |
| 15 | SIA-UC13 Hapus Data Mahasiswa | Generalization → | SIA-UC10 Kelola Data Mahasiswa |
| 16 | SIA-CO01 (Collaboration) | Realization → | SIA-UC08 Input Nilai Mata Kuliah |
| 17 | SIA-CO02 (Collaboration) | Realization → | SIA-UC09 Lihat KHS |