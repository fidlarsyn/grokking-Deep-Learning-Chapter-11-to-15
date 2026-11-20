**Bab 11: Neural Networks That Understand Language: king – man + woman == ?**
Membahas penerapan deep learning pada pemrosesan bahasa alami (NLP) untuk mengolah data teks menggunakan metode Bag-of-Words dan Embedding Layer. Melalui tugas klasifikasi sentimen ulasan film IMDB serta pemodelan isi kata kosong (fill-in-the-blank), jaringan mempelajari vektor kata (word embeddings) yang mengelompokkan kata berdasarkan kemiripan makna semantik dan menghasilkan sifat aljabar analogi kata (seperti $\text{king} - \text{man} + \text{woman} \approx \text{queen}$).

**Bab 12: Neural Networks That Write Like Shakespeare: Recurrent Layers for Variable-Length Data**
Mengatasi keterbatasan pendekatan *Bag-of-Words* yang mengabaikan urutan kata (*word order*) dengan memperkenalkan arsitektur **Recurrent Neural Network (RNN)**. Menggunakan matriks transisi rekuren, RNN mengalirkan memori tersembunyi (*hidden state*) dari satu langkah waktu (*timestep*) ke langkah berikutnya, serta dilatih menggunakan algoritma **Backpropagation Through Time (BPTT)** untuk memprediksi sekuens teks berpanjang variabel.

**Bab 13: Introducing Automatic Optimization: Let’s Build a Deep Learning Framework**
Berfokus pada rekayasa *framework deep learning* mandiri berbasis **dynamic computation graph** untuk mengotomatiskan kalkulasi turunan (*autograd*) dan optimasi pembaruan bobot. Menggunakan struktur data **Tensor**, *framework* ini mendukung operasi matematika rekursif serta menyediakan abstraksi *layer* seperti `Linear`, `Embedding`, dan `RNNCell` untuk mempermudah pembuatan arsitektur jaringan yang kompleks.

**Bab 14: Learning to Write Like Shakespeare: Long Short-Term Memory**
Mengatasi kendala *vanishing gradient* dan *exploding gradient* pada RNN saat melatih pemodelan bahasa tingkat karakter pada teks karya Shakespeare. Dengan memanfaatkan mekanisme pintu gerbang (*forget*, *input*, dan *output gates*) pada **sel LSTM** serta penerapan **Truncated BPTT**, jaringan mampu mempertahankan memori jangka panjang pada status sel (*cell state*) secara stabil tanpa mengalami degradasi sinyal gradien.

**Bab 15: Deep Learning on Unseen Data: Introducing Federated Learning**
Menjawab tantangan privasi data sensitif dengan menerapkan arsitektur terdesentralisasi **Federated Learning**, di mana model dikirimkan langsung ke perangkat lokal pengguna agar pelatihan dapat dilakukan tanpa memindahkan data mentah ke server pusat. Guna mencegah peretasan gradien individu, digunakan teknik **Secure Aggregation** dan **Homomorphic Encryption** untuk menjumlahkan pembaruan bobot dalam kondisi terenkripsi sebelum dideskripsi oleh server.


**Nama: Fidela Risyunira 
| NIM: 101032300001
| Class: TK-47-GAB**
