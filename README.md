# Filtering-Image-processing

Di bawah pengawasan ketat Dr. Arya Adhyaksa Waskita S.Si., M.Si.,Kami mahasiswa semester 5 tengah menyelesaikan tugas akhir mata kuliah Pengolahan Citra Digital. Dengan sabar dan teliti, beliau memberikan bimbingan kepada setiap mahasiswa. Beliau tidak hanya mengajarkan teori, tetapi juga mendorong mahasiswa untuk berpikir kritis dan inovatif dalam menerapkan ilmu pengolahan citra.

Program ini membahas tentang : 
1. Cara tentang menambahkan Noise pada gambar
2. Cara melakukan filtering

Algoritma yang digunakan :
1. Gausian Noise
2. Salt & Pepper Noise
3. Mean Filtering
4. Median Filtering

Referensi :
1. https://youtu.be/yQUwmLx6NGk?si=zkLOpnCzSIqKs_G0
2. https://youtu.be/xCHbcVUCYBI?si=Ou9oFUp2NYWsL8-_
3. https://youtu.be/StX_1iEO3ck?si=4l5IMnvdUEM3SwWi

Anggota Kelompok : 
1. Samirudin Annas Alfattah (221011402416)
2. Taufikurrohman (221011402405)
3. M. Syauqi Alfayyadh (221011402221)


# Gaussian Noise

Gaussian noise adalah jenis derau (noise) statistik yang memiliki fungsi distribusi probabilitas (PDF) yang mengikuti distribusi Gaussian (normal). Gaussian noise sering digunakan dalam berbagai bidang seperti pemrosesan sinyal, pemrosesan citra, dan telekomunikasi untuk memodelkan variasi acak atau kesalahan.
Nilai-nilai derau mengikuti distribusi Gaussian dengan rata-rata ( 𝜇 μ) dan deviasi standar ( 𝜎 σ).

![image](https://github.com/user-attachments/assets/199c165c-8c9d-4702-b588-940d9ab8c3ca)


# Salt & Pepper Noise
Salt and Pepper Noise adalah jenis derau (noise) yang muncul sebagai piksel putih (salt) dan piksel hitam (pepper) yang tersebar secara acak pada suatu citra. Noise ini disebut demikian karena kemunculannya menyerupai taburan garam (putih) dan merica (hitam) pada gambar. Gambar akan menampilkan bintik-bintik hitam (0) dan putih (255) yang tersebar secara acak pada area citra yang sebelumnya bersih.


# Mean Filtering
Mean Filtering adalah metode penyaringan citra yang digunakan untuk mengurangi noise dengan cara merata-ratakan nilai piksel dalam lingkungan (kernel) tertentu. Filter ini termasuk dalam kategori linear filters dan bekerja dengan menggantikan nilai setiap piksel dengan rata-rata dari piksel-piksel tetangganya dalam jendela filter. Mean filtering menggunakan jendela persegi panjang atau persegi dengan ukuran tertentu (misalnya, 3x3, 5x5, dll.).
Untuk kernel berukuran 𝑚 × 𝑛 m×n, nilai piksel keluaran 𝑔 ( 𝑥 , 𝑦 ) g(x,y) di posisi ( 𝑥 , 𝑦 ) (x,y) dihitung sebagai:

![image](https://github.com/user-attachments/assets/5ec9ff79-35f8-4995-8d11-b57b5d13ea74)


# Median Filtering
Median Filtering adalah metode penyaringan citra non-linear yang digunakan untuk mengurangi noise, terutama Salt & Pepper Noise, dengan menjaga tepi (edges) citra lebih baik dibandingkan dengan mean filtering. Teknik ini bekerja dengan menggantikan nilai piksel pusat dengan median dari piksel-piksel dalam lingkungan (kernel) tertentu. Median filtering menggunakan jendela persegi dengan ukuran tertentu (misalnya, 3x3, 5x5, dll.).
