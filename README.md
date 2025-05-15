Face_Detection_and_Recognition
Proyek ini bertujuan untuk mendeteksi wajah pada gambar menggunakan metode Haar Cascade dari OpenCV. Gambar input akan dikonversi ke format grayscale terlebih dahulu, kemudian dilakukan proses pencarian wajah menggunakan model cascade classifier.

Fitur Utama:

Mendeteksi wajah dalam gambar.

Mengubah ukuran gambar menjadi ukuran tetap 250x250 piksel.

Parameter deteksi wajah dapat disesuaikan, seperti scale factor, jumlah tetangga minimum, dan ukuran minimum wajah.

Petunjuk Penggunaan:

Persiapan Library
Pastikan Python dan library berikut sudah terpasang:

opencv-python

numpy

matplotlib (opsional, digunakan untuk visualisasi)

Menjalankan Notebook
Buka file Face_Detection_Recognition.ipynb dan jalankan setiap sel secara berurutan.

Deteksi Wajah
Gunakan fungsi detect_faces(image_gray) untuk melakukan deteksi wajah pada gambar yang sudah dalam format grayscale.

