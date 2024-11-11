# master_plan

A new Flutter project.

hasil praktikum pertama
![gif yuda](./image/01.gif)

2. mengelompokkan semua model data yang digunakan dalam aplikasi ke dalam satu berkas data_layer.dart
daripda mengimportnya secara terpisah.
3. digunakan untuk menyimpan objek Plan yang berisi daftar tugas (tasks) dan nama rencana,
Plan dibuat sebagai konstanta agar tugas-tugasnya dapat tetap terjaga dan tidak secara langsung diubah tanpa melalui pengaturan ulang di setState

4. ListTile digunakan untuk menampilkan setiap tugas (task) dalam daftar tugas yang ada di plan.
ListTile ini memungkinkan pengguna untuk mengedit deskripsi tugas melalui TextFormField
![Secreenshot yuda1](image/01.png)


5. Pada langkah 11 initState digunakan untuk menginisialisasi ScrollController dan menambahkan listener yang menutup keyboard ketika pengguna melakukan scroll.
   Pada langkah 13, dispose dipakai untuk membersihkan ScrollController ketika widget tidak lagi digunakan (misalnya ketika layar berubah).
   praktikum ke-9


TUGAS PRAKTIKUM 2

1. pada hasilnya menampilkan jumlah kolom output yang di centang dan juga jumlah tasks dari daftar tugas dengan progres di bagian bawah layar.
![Secreenshot yuda1](image/02.png)

2. InheritedNotifier adalah varian dari InheritedWidget yang memungkinkan untuk memantau perubahan pada ValueNotifier.
ValueNotifier dapat memperbarui widget yang berlangganan secara otomatis saat ada perubahan pada data Plan.

3. memungkinkan aplikasi untuk memberikan umpan balik langsung kepada pengguna mengenai progres tugas yang telah mereka selesaikan.
Dengan informasi ini, pengguna dapat melihat jumlah tugas yang sudah selesai dibandingkan dengan jumlah total, sehingga memberikan gambaran jelas
tentang kemajuan mereka dalam menyelesaikan seluruh tugas.

4. Langkah ini menambahkan footer yang menunjukkan status penyelesaian tugas (completenessMessage).
   Dengan wrap widget Expanded di sekitar _buildList dalam Column, layout memungkinkan tampilan daftar tugas dengan progres di bagian bawah layar.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
