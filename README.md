# Jarkom_Modul4_Lapres_E04
Repository untuk Laporan Resmi Praktikum Modul 3 Jarkom 2020 - E04

* Michael Ricky
  0511184000078
  
* Qatrunada Qori Darwati
  05111840000059

## VLSM
Berikut gambar topologi pembagian subnet untuk metode perhitungan VLSM.

![]()

**Langkah 1** - Tentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan lakukan labelling netmask berdasarkan jumlah IP yang dibutuhkan.

![]()

**Langkah 2** - Subnet besar yang dibentuk memiliki NID 192.168.0.0 dengan netmask /19. Hitung pembagian IP berdasarkan NID dan netmask tersebut menggunakan pohon lalu lakukan subnetting. Hasilnya adalah seperti pada gambar di bawah.

![]()

Dari pohon tersebut diperoleh pembagian IP sebagai berikut.

![]()

### Implementasi pada CPT
Berikut langkah-langkah implementasi metode perhitungan VLSM yang dilakukan pada CPT.

**Langkah 1** - Buat topologi seperti permintaan soal.

**Langkah 2** - Setting interface pada semua router, server, dan client sesuai dengan pembagian IP yang telah ditentukan.

**Langkah 3** - Tambahkan static route. Dimana SURABAYA harus dikenalkan pada A03, A04, A05, A07, A08, A09, A10, A11, A12, A13, dan server MALANG. Lalu PASURUAN harus dikenalkan pada A04 dan A08. BATU dikenalkan kepada A09, A12, A13, dan server MALANG. Terakhir KEDIRI pada A12.

**Langkah 4** - Testing dengan cara ping.

## CIDR
Berikut gambar topologi pembagian subnet untuk metode perhitungan CIDR.

![]()

**Langkah 1** - Tentukan subnet yang ada dalam topologi dan lakukan labelling netmask terhadap masing-masing subnet. Lalu gabungkan subnet yang paling bawah di dalam topologi. Ulangi penggabungan ini hingga sebuah subnet sebesar 1 topologi terbentuk. 

**Langkah 2** - Dari proses penggabungan yang telah dilakukan, didapatkan sebuah subnet besar dengan netmask /21. Kali ini dapat menggunakan NID 192.168.0.0, netmask 255.255.248.0.

**Langkah 3** - Hitung pembagian IP dengan pohon berdasarkan penggabungan subnet yang telah dilakukan.

![]()

**Langkah 4** - Berdasarkan penghitungan, maka didapatkan pembagian IP sebagai berikut.

![]()
