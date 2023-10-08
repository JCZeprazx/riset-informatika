# Topik Penelitian
Architectural Support for Dynamic Linking

<hr>

### Statement
Semua perangkat lunak saat ini bergantung pada library. Semua library dimuat memory dan terhubung secara dinamis saat perangkat lunak kita dijalankan. Keuntungan menggunakan library yang dinamis sangat banyak seperti dapat menggunakan ulang komponen, dapat memperbarui fitur dari library tanpa mengubah kode utama, dan masih banyak lagi. Dibalik keuntungan tersebut dynamic library memiliki kekurangan pada performa dan beban memory yang berat. Untuk mengurangi kekurangan tersebut kita dapat mengurangi intruksi dan data-cache, TLB, dan branch predictor.

### Persoalan Praktis 
- Performa berkurang saat memanggil sebuah fungsi secara dinamis.
- Beban memori yang timbul saat membaca alamat sebuah fungsi yang dijalankan.

### Research Questions
- Bagimana cara memaksimalkan kinerja library tanpa mengurangi peforma?
- Apa saja yang dibutuhkan untuk mempercepat pemanggilan sebuah fungsi?

