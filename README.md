# PCD-Transformasi Citra dan Perbaikan citra pada domain frekuensi
Proyek ini menampilkan teknik pengolahan citra menggunakan transformasi Fourier dan berbagai filter, seperti Ideal, Butterworth, Gaussian, dan unsharp masking. Filter ini diterapkan pada gambar `oyencat.jpg` untuk melakukan penghalusan, penajaman, dan pengurangan noise.

## Prasyarat
Instal pustaka berikut:
```bash
  pip install numpy opencv-python matplotlib scipy
```

## Fitur Utama
1. **Transformasi Fourier**: Mengubah gambar ke domain frekuensi dan menampilkan spektrum magnitudo.
2. **Filter Lowpass dan Highpass**: Ideal, Butterworth, dan Gaussian untuk menyaring frekuensi gambar.
3. **Unsharp Masking**: Menajamkan gambar dengan mengurangi versi buram dari gambar asli.
4. **Selective Filtering**: Mengurangi noise sambil mempertahankan ketajaman tepi.

## Cara Penggunaan

1. Siapkan gambar `oyencat.jpg`.
2. Jalankan kode untuk melihat hasil filtering pada gambar asli.

Hasilnya akan menunjukkan gambar asli berdampingan dengan gambar hasil filter atau transformasi.
