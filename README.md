# Pertemuan 12 - File I/O dan Error Handling

Nama: Inayatul Sholihah
NIM: 2225250057
Kelas: PMAT A

## Tujuan
Membaca, memvalidasi, mengolah, dan menulis data file dengan Python.

## Format File Input
NIM,nilai

## Cara Menjalankan
python3 tugas/rekap_nilai_file.py

## Error yang Ditangani
- FileNotFoundError
- ValueError

## Test Case

| Kondisi | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|
| File nilai tersedia | Data berhasil dibaca | Data berhasil dibaca | Berhasil |
| Nilai tidak valid (abc) | Baris dilewati | Baris A004 dilewati | Berhasil |
| Data valid diproses | Rekap berhasil dibuat | Rekap berhasil dibuat | Berhasil |

## Refleksi
Error ValueError terjadi ketika nilai tidak dapat dikonversi menjadi float. Program menangani error tersebut dengan melewati baris yang tidak valid sehingga proses membaca data tetap berjalan.