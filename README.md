# TextToImage

Aplikasi untuk membuat gambar menggunkan perintah text

Direkomendasikan Menggunakan Google Colab https://colab.research.google.com/

Pada Colab Ganti Type Runtime menjadi GPU atau T4 GPU

File dibagi menjadi beberapa paket, tergantung model yang saya siapkan, pilih salah satu saja mau buat gambar apa, silahkan pilih sesuai kebutuhan

----
# Keunggulan

+ Sudah disertai program penerjemah jadi bisa menggunakan bahasa indonesia
+ Menggunakan StableDiffusionPipeline sehingga gambar lebih bagus
+ Dijalankan di google colab, tinggal running
+ Sudah tersedia form input sehingga modifikasi isi sangat mudah
+ Disertai panduan

----

# Pengetahuan

Program ini menggunakan diffuser untuk mengelolah gambar

**Diffuser** adalah model yang digunakan untuk menghasilkan teks ke gambar, dan pada umumnya, cara kerjanya adalah sebagai berikut:

1. Input Teks: Anda memberikan teks deskripsi atau prompt sebagai input. Teks ini akan menjadi panduan untuk menghasilkan gambar.

2. Tokenisasi dan Encoding: Teks input akan di-tokenisasi menjadi potongan-potongan yang lebih kecil (token) yang akan dimengerti oleh model. Ini termasuk kata-kata dalam teks dan tanda baca. Setiap token akan diubah menjadi representasi numerik yang dapat dimengerti oleh model (misalnya, embedding vektor).

3. Generasi Gambar: Model Diffuser akan menerima representasi numerik dari teks sebagai input dan akan menghasilkan gambar sebagai output. Ini adalah langkah utama di mana model menggunakan informasi dalam teks untuk menghasilkan gambar yang sesuai.

4. Decoding: Gambar yang dihasilkan oleh model adalah representasi numerik dari gambar tersebut. Untuk melihatnya sebagai gambar visual, perlu dilakukan proses decoding. Ini melibatkan mengonversi representasi numerik menjadi gambar dalam format yang dapat ditampilkan.

5. Tampilan atau Penyajian: Setelah gambar didekode, Anda dapat menampilkan atau menyajikannya kepada pengguna, misalnya dengan menampilkan gambar di layar.

Penting untuk dicatat bahwa Diffuser biasanya menggunakan teknik-teknik generatif berbasis GAN (Generative Adversarial Network) atau teknik lainnya yang memungkinkan model untuk menghasilkan gambar-gambar yang realistis dan sesuai dengan deskripsi teks.

Selain itu, beberapa model Diffuser dapat memiliki variasi dan penyesuaian tertentu tergantung pada tugas yang ingin dicapai, seperti menghasilkan gambar anime berdasarkan deskripsi teks atau menghasilkan gambar realistik berdasarkan deskripsi objek dalam teks.

Cara kerja model Diffuser dapat bervariasi tergantung pada model dan implementasinya, tetapi intinya adalah menggunakan teks sebagai panduan untuk menghasilkan gambar yang sesuai.
