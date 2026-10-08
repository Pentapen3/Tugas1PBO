# PEMROGRAMAN BERORIENTASI OBJEK

## Biodata

- **Nama** : Prevansyah Sjafar
- **NIM** : 4525210057
- **Program Studi** : Teknik Informatika
- **Kelas** : A
- **Mata Kuliah** : Pemrograman Berorientasi Objek
- **Dosen Pengampu** : Adi Wahyu Pribadi, S.Si., M.Kom

## Teknologi yang Digunakan

Tugas dibuat menggunakan dua bahasa pemrograman berikut:

- **Java** dengan Java Development Kit (JDK).
- **PHP** dengan PHP interpreter.

Visual Studio Code digunakan sebagai IDE dengan extension Java Red Hat,
PHP Intelephense, Prettier, dan Error Lens.

## Materi Pembelajaran

Repository ini berisi penerapan konsep pemrograman berorientasi objek
tugas 01 sampai tugas 06:

1. Class dan Object
2. Encapsulation dan Constructor
3. Inheritance dan Method Overriding
4. Polimorfisme
5. Asosiasi, Agregasi, dan Komposisi
6. Abstract Class dan Interface

Setiap tugas dibuat dalam versi Java dan PHP. Penjelasan implementasi yang
lebih rinci tersedia pada README di masing-masing folder tugas.

---

## Tugas 01 - Class dan Object

### Deskripsi Tugas

Program ini menggunakan class `iPhone` sebagai cetak biru object. Dua object
iPhone dibuat dengan warna dan kapasitas penyimpanan yang berbeda, kemudian
informasinya ditampilkan melalui method `getColor()` dan `getStorage()`.

### Screenshot Hasil Run

#### Hasil Run Java

![Hasil run Java](01Class/img/runjava.png)

#### Hasil Run PHP

![Hasil run PHP](01Class/img/runphp.png)

---

## Tugas 02 - Encapsulation dan Constructor

### Deskripsi Tugas

Program ini menerapkan encapsulation pada class `Mahasiswa`. Property
`nama`, `nim`, dan `umur` dibuat `private`, sehingga akses dan perubahan data
dilakukan melalui getter dan setter.

### Screenshot Hasil Run

#### Hasil Run Java

![Hasil run Java](02Constructor/img/runjava.png)

#### Hasil Run PHP

![Hasil run PHP](02Constructor/img/runphp.png)

---

## Tugas 03 - Inheritance dan Method Overriding

### Deskripsi Tugas

Program ini menerapkan inheritance dan method overriding melalui dua contoh.
Class `BangunDatar` diwarisi oleh `Lingkaran`, `Persegi`, dan `Segitiga`.
Selain itu, class `MahasiswaInternational` mewarisi class `Mahasiswa`.

### Screenshot Hasil Run

#### Hasil Run Java

![Hasil run Java Bangun Datar](03inheritance/img/runjava1.png)

![Hasil run Java Mahasiswa](03inheritance/img/runjava2.png)

#### Hasil Run PHP

![Hasil run PHP Bangun Datar](03inheritance/img/runphp1.png)

![Hasil run PHP Mahasiswa](03inheritance/img/runphp2.png)

---

## Tugas 04 - Inheritance dan Polimorfisme

### Deskripsi Tugas

Program ini menerapkan inheritance dan polimorfisme pada class `Handphone`.
Class `Smartphone` dan `FeaturePhone` mewarisi `Handphone`, kemudian
mengubah perilaku method `nyalakan()`, `matikan()`, dan `telepon()`.

### Screenshot Hasil Run

#### Hasil Run Java

![Hasil run Java](04polymorphism/img/runjava.png)

#### Hasil Run PHP

![Hasil run PHP](04polymorphism/img/runphp.png)

---

## Tugas 05 - Asosiasi, Agregasi, dan Komposisi

### Deskripsi Tugas

Program ini menerapkan hubungan antar-object menggunakan tiga jenis relasi,
yaitu asosiasi, agregasi, dan komposisi.

### Screenshot Hasil Run

#### Hasil Run Java

![Hasil run Java](05asosiasikomposisi/img/runjava.png)

#### Hasil Run PHP

![Hasil run PHP](05asosiasikomposisi/img/runphp.png)

---

## Tugas 06 - Abstract Class dan Interface

### Deskripsi Tugas

Program ini menerapkan abstract class dan interface. Abstract class `Vehicle`
menjadi parent class untuk berbagai jenis kendaraan, sedangkan interface
`Movable` dan `Fuelable` menentukan kemampuan yang dapat dimiliki object.

### Screenshot Hasil Run

#### Hasil Run Java

![Hasil run Java](06abstractinterface/img/runjava.png)

#### Hasil Run PHP

![Hasil run PHP](06abstractinterface/img/runphp.png)