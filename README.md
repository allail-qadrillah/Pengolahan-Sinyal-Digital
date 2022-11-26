
# Project Akhir Mata Kuliah Pengolahan Sinyal Digital
Diajukan untuk melengkapi sebagian tugas dari matakuliah
Pengolahan Sinyal Digital (PSD)

## Overview 📃
[1. Latar Belakang](https://github.com/allail-qadrillah/Pengolahan-Sinyal-Digital#latar-belakang)
[2. Hasil](https://github.com/allail-qadrillah/Pengolahan-Sinyal-Digital#hasil-)
[3. Kesimpulan](https://github.com/allail-qadrillah/Pengolahan-Sinyal-Digital#kesimpulan-)

### Latar Belakang 
Penelitian ini memanfaatkan **Filter Fast Fourier Transform (FFT)** dimana prosesnya banyak sekali
digunakan seperti pada signal 5G, Radar hingga proses Repository ini sampai kepada anda. Penggunaan metode
filter FFT ini banyak digunakan untuk menghilangkan noise dari sinyal.

Untuk mengatasi permasalahan tentang bagaimana pengaruh klasifikasi
sinyal EEG pada penderita autis dan normal, maka kami usulkan penelitian ini
menggunakan metode FFT karena metode ini sangat efisien untuk menghitung
koefisien dari Discrete ke suatu Finite sekuen dari data kompleks. Tujuannya
untuk menghasilkan hasil klasifikasi sinyal EEG dengan menerapkan filter FFT
pada dataset dengan konteks penderita autis dan normal.


### Hasil 🙌
1️⃣ Sinyal EEG Mentah Anak Normal
![EEG NORMAL MENTAH](https://user-images.githubusercontent.com/89723505/204079198-5c1521a3-e851-46bd-980f-48bda25dcd3b.png)
2️⃣ Sinyal EEG Hasil Filter FFT Anak Normal
![EEG NORMAL FILTERS](https://user-images.githubusercontent.com/89723505/204079216-460ec982-6c30-4f8a-a038-2cc6ff7eb92a.png)
1️⃣ Sinyal EEG Mentah Anak Autis
![EEG AUTIS MENTAH](https://user-images.githubusercontent.com/89723505/204078684-2b385cdf-ddaf-4a46-8175-2431d6c739b6.png)
2️⃣ Sinyal EEG Hasil Filter FFT Anak Autis
![EEG AUTIS FILTER](https://user-images.githubusercontent.com/89723505/204079090-17dd16cb-dbdd-407e-a984-785057401319.png)

### Kesimpulan ✨
s filterisasi menggunakan metode Fast Fourier Transform (FFT) terbukti sangat efektif untuk menghilangkan artefak pada sinyal inputnya sehingga lebih terlihat nyata tanpa adanya noise yang telah ditekan. Saat sinyal EEG pada penderita autis bergabung dengan noise diperoleh rentang amplitudo dan peak to peak nya dari 1000 sampai -1000. Dan saat sesudah difilter menggunakan metode FFT rentang amplitude dan peak to peaknya turun menjadi 80 sampai -60.
