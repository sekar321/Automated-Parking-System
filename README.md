# Automated-Parking-System
# Automated Parking System Using Image Processing

## Pendahuluan

Proyek ini bertujuan untuk mengembangkan sistem parkir otomatis yang dapat mendeteksi ruang parkir dengan menggunakan teknik pengolahan citra. Sistem ini dirancang untuk mengurangi kebutuhan tenaga manusia dan meningkatkan efisiensi penggunaan ruang parkir. Dengan masalah peningkatan kemacetan lalu lintas dan kurangnya ruang parkir di kota-kota metropolitan, sistem ini sangat diperlukan untuk memberikan informasi yang relevan tentang ketersediaan ruang parkir kepada pengemudi.

## Isi

### 1. Sistem Parkir Otomatis dengan Pengolahan Citra
- *Sistem Pengolahan Citra*: 
  - Sistem ini menggunakan kamera yang dipasang pada posisi tinggi dan tetap di dalam parkir untuk mengambil gambar parkir kosong dan parkir yang berisi mobil. Gambar-gambar ini kemudian dibandingkan untuk menentukan jumlah ruang parkir yang tersedia.
  
- *Pengolahan Citra*: 
  - Proses pengolahan citra melibatkan beberapa langkah, termasuk:
    - *Pengambilan Gambar Referensi*: Gambar parkir kosong diambil sebagai referensi.
    - *Pengambilan Gambar Parkir yang Berisi Mobil*: Gambar parkir yang berisi mobil diambil.
    - *Perbandingan Gambar*: Gambar parkir yang berisi mobil dibandingkan dengan gambar referensi untuk menentukan jumlah ruang parkir yang tersedia.
  
- *Penggunaan MATLAB*: 
  - Sistem ini menggunakan MATLAB sebagai platform perangkat lunak untuk mengolah citra dan menghitung jumlah ruang parkir yang tersedia.

### 2. Sistem Pengolahan Citra dalam Detail
- *Pengambilan Gambar*: 
  - Gambar parkir diambil dari kamera yang dipasang di atas parkir.
  - *Pengolahan Citra*: 
  - Gambar diolah menjadi citra abu-abu dan kemudian citra biner untuk memisahkan objek-objek yang berbeda.
  - Citra biner diperoleh dengan menggunakan teknik thresholding untuk memisahkan objek mobil dari latar belakang.
  
- *Deteksi Objek*: 
  - Deteksi objek dilakukan dengan menganalisis blob dalam citra biner untuk menghitung jumlah mobil yang ada di dalam parkir.

### 3. Sistem Panduan Parkir
- Sistem ini juga dilengkapi dengan sistem panduan parkir yang dapat menunjukkan kepada pengemudi tempat parkir yang tersedia.
- Pengemudi dapat menerima informasi real-time tentang ketersediaan ruang parkir melalui sistem ini.

## Kesimpulan

Proyek ini berhasil mengembangkan sistem parkir otomatis yang efektif menggunakan teknik pengolahan citra. Sistem ini dapat mengurangi kebutuhan tenaga manusia dan meningkatkan efisiensi penggunaan ruang parkir. Dengan menggunakan kamera dan perangkat lunak MATLAB, sistem ini dapat memberikan informasi real-time tentang ketersediaan ruang parkir kepada pengemudi, sehingga mengurangi waktu pencarian parkir dan mengurangi kemacetan lalu lintas di sekitar parkir. Proyek ini menunjukkan bahwa pengolahan citra dapat digunakan dalam berbagai aplikasi, termasuk sistem parkir, untuk meningkatkan efisiensi dan kenyamanan pengguna.
