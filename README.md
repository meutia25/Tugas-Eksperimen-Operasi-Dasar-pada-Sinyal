# Operasi Dasar pada Sinyal dan Citra

## Nama Mahasiswa
- Nama          : Meutia Mirah Asih
- NIM           : 452024618092
- Program Studi : Teknik Informatika

## Deskripsi Singkat Project
Project ini bertujuan untuk mempelajari dan mengimplementasikan operasi dasar pada sinyal 1D dan citra 2D menggunakan bahasa pemrograman Python. Operasi yang dilakukan meliputi penjumlahan, penggeseran (shift), amplifikasi, serta pengujian sifat sistem linier melalui homogenitas dan additivitas. Selain implementasi program, project ini juga menganalisis pengaruh setiap operasi terhadap karakteristik sinyal dan citra serta menghubungkannya dengan aplikasi nyata dalam bidang pengolahan sinyal digital dan pengolahan citra.

## Library yang Digunakan
- NumPy
- Matplotlib
- OpenCV (cv2)
- Scikit-Image (skimage)
- Pandas

## Cara Menjalankan Notebook
1. Pastikan Python 3 telah terinstal pada komputer.
2. Install seluruh library yang dibutuhkan:
   pip install numpy matplotlib opencv-python scikit-image pandas
3. Jalankan Jupyter Notebook:
   jupyter notebook
4. Buka file notebook:
   Operasi_Sinyal_Citra.ipynb
5. Jalankan setiap cell secara berurutan menggunakan tombol Run atau Shift + Enter.
6. Amati hasil visualisasi, tabel, dan analisis yang dihasilkan pada setiap bagian praktikum.

## Struktur Folder Project

Tugas Eksperimen Operasi Dasar pada Sinyal/
1. notebook/
Tugas Eksperimen Operasi Dasar pada Sinyal.ipynb
2. images/
citra_yang_digunakan.jpg
3. report/
Laporan_Tugas Eksperimen Operasi Dasar pada Sinyal_Meutia Mirah Asih_452024618092_C1.pdf
4. README.md
5. requirements.txt

## Ringkasan Hasil Eksperimen

### Operasi pada Sinyal 1D
- Sinyal diskrit berhasil dibuat menggunakan fungsi sinus dan unit step..
- Operasi penjumlahan menghasilkan sinyal baru yang merupakan kombinasi dari kedua sinyal masukan.
- Operasi penggeseran mengubah posisi sinyal tanpa mengubah bentuk dasarnya.
- Operasi amplifikasi mengubah amplitudo sinyal sesuai nilai faktor pengali (α).

### Operasi pada Citra 2D
- Citra berhasil ditampilkan dan dianalisis berdasarkan ukuran, tipe data, serta nilai pikselnya.
- Operasi penjumlahan citra menghasilkan citra baru yang menggabungkan informasi dari dua citra berbeda.
- Operasi penggeseran (translasi) memindahkan posisi objek pada citra tanpa mengubah bentuk objek.
- Operasi amplifikasi citra memengaruhi tingkat kecerahan (brightness) dan distribusi histogram citra.
### Uji Sistem Linier 
- Sistem T(x) = 2x memenuhi sifat homogenitas dan additivitas sehingga termasuk sistem linier.
- Sistem T(x) = x² tidak memenuhi homogenitas maupun additivitas sehingga termasuk sistem non-linier.
- Hasil pengujian menunjukkan bahwa linearitas sistem sangat memengaruhi kemudahan analisis dan prediksi keluaran sistem.

### Studi Kasus
- Studi kasus Brightness Enhancement pada citra menunjukkan bahwa operasi amplifikasi dapat digunakan untuk meningkatkan kecerahan citra.
- Nilai faktor amplifikasi yang terlalu besar dapat menyebabkan clipping sehingga sebagian detail citra hilang.

## Kesimpulan Singkat
Berdasarkan hasil eksperimen, operasi dasar pada sinyal 1D dan citra 2D seperti penjumlahan, penggeseran, dan amplifikasi dapat diimplementasikan dengan baik menggunakan Python. Pengujian sistem linier menunjukkan bahwa suatu sistem harus memenuhi sifat homogenitas dan additivitas agar dapat dikategorikan sebagai sistem linier. Selain membantu memahami konsep dasar Pengolahan Sinyal Digital, eksperimen ini juga menunjukkan bahwa operasi-operasi sederhana memiliki peran penting dalam berbagai aplikasi nyata, seperti pengolahan audio, pengolahan citra, dan sistem komunikasi.
