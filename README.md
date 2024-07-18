# Proyek_Klasifikasi_Image_from_GDSC_by Isa Aulia Almadani

## Project Overview: 	Klasifikasi Gambar Butir Padi Menggunakan Mobile Net V2
Proyek ini berfokus pada klasifikasi gambar butir padi menggunakan arsitektur model Mobile Net V2 yang telah dilatih sebelumnya. Mobile Net V2 dipilih karena efisiensi dan performanya yang baik dalam tugas-tugas klasifikasi gambar pada perangkat dengan keterbatasan sumber daya.

## Tujuan Proyek
Tujuan dari proyek ini adalah untuk mengembangkan model yang mampu mengklasifikasikan gambar butir padi dengan akurasi tinggi. Model ini diharapkan dapat membantu dalam proses seleksi dan pengawasan kualitas butir padi secara otomatis.

## Fitur Utama
* Import Library
Mengimpor pustaka-pustaka yang diperlukan untuk pemrosesan data, pelatihan model, dan visualisasi hasil.
* Import Dataset from Kaggle
Mengunduh dan memuat dataset gambar butir padi dari Kaggle untuk digunakan dalam pelatihan dan pengujian model.
* Preprocessing
Melakukan praproses pada dataset, termasuk perubahan ukuran gambar, normalisasi, dan augmentasi data untuk meningkatkan kinerja model.
* Building Model with Pretrained Model
Menggunakan Mobile Net V2 yang telah dilatih sebelumnya sebagai dasar untuk membangun model klasifikasi. Langkah ini melibatkan fine-tuning model untuk menyesuaikan dengan dataset butir padi.
* Plot Visualization
Membuat visualisasi data dan hasil pelatihan model, termasuk grafik akurasi dan kehilangan (loss) selama proses pelatihan.
* Predict Image
Menggunakan model yang telah dilatih untuk memprediksi kelas dari gambar butir padi baru, dan menampilkan hasil prediksi tersebut.
## Teknologi yang Digunakan
* Python: Bahasa pemrograman utama yang digunakan dalam proyek ini.
* TensorFlow/Keras: Framework deep learning yang digunakan untuk membangun dan melatih model.
* Kaggle: Sumber dataset gambar butir padi.
* Matplotlib/Seaborn: Pustaka visualisasi yang digunakan untuk membuat plot dan grafik.
## Rencana Pengembangan
* Mengoptimalkan model dengan teknik-teknik tambahan seperti fine-tuning dan hyperparameter tuning.
* Menerapkan teknik augmentasi data yang lebih lanjut untuk meningkatkan kinerja model.
* Mengintegrasikan model dengan aplikasi berbasis web untuk demo prediksi gambar secara real-time.
## Hasil yang Diharapkan
* Menghasilkan model klasifikasi gambar butir padi dengan akurasi tinggi.
* Memudahkan proses seleksi dan pengawasan kualitas butir padi melalui otomatisasi.
* Memberikan kontribusi terhadap pengembangan teknologi pertanian berbasis AI di Indonesia.
