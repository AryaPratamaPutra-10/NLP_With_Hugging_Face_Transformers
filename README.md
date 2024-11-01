<h1 align="center"> NLP With Hugging Face Transformers </h1>
<p align="center"> Berisi tentang pipeline dari HuggingFace Transformers untuk keperluan NLP (Natural Language Processing) </h1>

<div align="center">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">
</div>

<div align="center">
<h2 align="center"> Analisis </h2>
<p1>- Zero-Shot Classification
Merupakan jenis klasifikasi dengan metode Zero-Shot yang dimana metode ini mengklasifikasi teks ke dalam label yang diberikan sesuai dengan kategorinya dan semakin mendekati 1 berarti semakin akurat, metode ini mencoba menghubungkan konsep dengan hubungan kata - kata </p1>
<p2>- Jawaban akan pertanyaan yang dijawab oleh model tergantung dari konteks yang kita masukkan semakin relevan konteks yang kita masukkin semakin akurat model memberikan jawaban</p2>
<p3>- generator ("text-generation") dapat melakukan fungsi untuk melatih model untuk menghasilkan prediksi kata - kata yang logis dengan teks yang telah kita masukkin sebelumnya </p3>
<p4> - distilgpt2 adalah model yang bisa menghasilkan kalimat lanjutan dari kalimat yang kita masukkin dan kalimat yang dihasilkan juga berbeda - beda dan disini saya juga bisa menentukan maksimun token yang akan dihasilkan dan berapa banyak kalimat yang mau dihasilkan </p4>
<p5>- unmasker = pipeline("fill-mask") model ini dapat memprediksi kata yang bisa mengisi kalimat yang kosong dalam contoh yang saya buat saya memprediksi 3 kata yang mungkin bisa mengisi kekosongan kalimat berikut "in the future Artificial Intelligence will replace <mask> human.</p5>
<p6>- ner adalah fungsi yang dapat mengidentifikasi entitas di dalam text yang saya masukkin lalu mengelompokkan jenis entitas yang terdapat di dalam text </p6>
<p7>- "question-answering" merupakan fungsi yang dapat menjawab pertanyaan dari context yang kita berikan dan jawabannya akan sesuai context yang dimasukkan </p7>
<p8> - Classifier ("sentiment-analysis") adalah fungsi yang dapat menganalisa sentimen dari kalimat yang saya masukkin dan hasilnya akan diklasifikasikan menjadi label positive ataupu negatif dan apabila scorenya mendekati 1 semakin kuat sentiment nya positive </p8>
<p9> - Summarizer merupakan fungsi untuk meringkas teks dari konteks teks yang kita masukkin </p9>
<p10> - Translator merupakan fungsi untuk menerjemahkan bahasa dari teks dan bahasanya bisa kita masukkin di sini saya coba menerjemahkan teks bahasa indonesia lalu ditampilkan ke bahasa inggris </p10>


Kesimpulan = Dalam menggunakan model NLP pemilihan segmentasi teks sangatlah penting mulai dari kalimat, teks, konteks, pertanyaan karena semuanya saling berkesinambungan dan semakin lengkap atau bagus sebuah data yang disini saya gunakan adalah sebuah kumpulan teks maka semakin bagus juga model akan bekerja untuk melakukan segmentasi teks nya serta akurasi yang diharapkan semakin tinggi. Ada berbagai jenis model pipeline yang bisa kita gunakan untuk NLP tergantung kebutuhan ada Translator untuk menerjemahkan antar bahasa, qa untuk menjawab pertanyaan contoh penggunaannya ada di chtbot, ada classifier yang digunakan untuk menentukan apakah kalimatnya berisi segmentasi postitif atau negatif biasanya digunakan untuk analisis rating sebuah produk di marketplace berdasarkan ulasan pelanggan, ada summarizer untuk meringkas sebuah teks contoh penggunaanya di pharaprase.
</div>
