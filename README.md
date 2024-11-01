<h1 align="center"> NLP With Hugging Face Transformers </h1>
<p align="center"> Berisi tentang pipeline dari HuggingFace Transformers untuk keperluan NLP (Natural Language Processing) </h1>

<div align="center">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">
</div>

<div>
<h2 align="center"> Analisis </h2>
<p1 align="left"> - Zero-Shot Classification
Merupakan jenis klasifikasi dengan metode Zero-Shot yang dimana metode ini mengklasifikasi teks ke dalam label yang diberikan sesuai dengan kategorinya dan semakin mendekati 1 berarti semakin akurat, metode ini mencoba menghubungkan konsep dengan hubungan kata - kata </p1>
  
<p2 align="left">- Jawaban akan pertanyaan yang dijawab oleh model tergantung dari konteks yang kita masukkan semakin relevan konteks yang kita masukkin semakin akurat model memberikan jawaban </p2>

<p3 align="left">- generator ("text-generation") dapat melakukan fungsi untuk melatih model untuk menghasilkan prediksi kata - kata yang logis dengan teks yang telah kita masukkin sebelumnya </p3>

<p4 align="left" > - distilgpt2 adalah model yang bisa menghasilkan kalimat lanjutan dari kalimat yang kita masukkin dan kalimat yang dihasilkan juga berbeda - beda dan disini saya juga bisa menentukan maksimun token yang akan dihasilkan dan berapa banyak kalimat yang mau dihasilkan. Model ini bisa membantu kita membuat sebuah keterangan yang lengkap dari kalimat yang sudah kita masukkin sebelumnya </p4>

<p5 align="left">- unmasker = pipeline("fill-mask") model ini dapat memprediksi kata yang bisa mengisi kalimat yang kosong dalam contoh yang saya buat saya memprediksi 3 kata yang mungkin bisa mengisi kekosongan kalimat berikut "in the future Artificial Intelligence will replace <mask> human.</p5>

<p6 align="left">- ner adalah fungsi yang dapat mengidentifikasi entitas di dalam text yang saya masukkin lalu mengelompokkan jenis entitas yang terdapat di dalam text. Di praktek yang saya lakukan entitas yang diidentifikasi adalah subject(orang), organisai, bahkan negara dan perusahaan diidentifikasi sebagai organisai   </p6>

<p7 align="left">- "question-answering" merupakan fungsi yang dapat menjawab pertanyaan dari context yang kita berikan dan jawabannya akan sesuai context yang dimasukkan. Pertanyaan yang diajukan juga nantinya harus sesuai dengan konteks yang kita masukkin dan apabila pertanyaan yang dimasukkin tidak bisa dianalisis model dengan context yang dimasukkin maka output jawaban yang diberikan oleh model akan sembarangan </p7>

<p8 align="left"> - Classifier ("sentiment-analysis") adalah fungsi yang dapat menganalisa sentimen dari kalimat yang saya masukkin dan hasilnya akan diklasifikasikan menjadi label positive ataupu negatif dan apabila scorenya mendekati 1 semakin kuat sentiment nya positive. Model ini bisa membantu kita dalam menganalisis ulasan untuk membuat sebuah rating seperti di marketplace </p8>

<p9 align="left"> - Summarizer merupakan fungsi untuk meringkas teks dari konteks teks yang kita masukkin. Dari percobaan yang saya lakukan di sini model ini tidak bisa dimuat context yang banyak apabila context yang dimasukkin terlalu banyak model tidak bisa bekerja  </p9>

<p10 align="left"> - Translator merupakan fungsi untuk menerjemahkan bahasa dari teks dan bahasanya bisa kita masukkin di sini saya coba menerjemahkan teks bahasa indonesia lalu ditampilkan ke bahasa inggris. Model ini bisa digunakan untuk mentranslator banyak bahasa contoh penggunaannya ada di google translate ataupun deepL translator </p10>


Kesimpulan = Dalam menggunakan model NLP pemilihan segmentasi teks sangatlah penting mulai dari kalimat, teks, konteks, pertanyaan karena semuanya saling berkesinambungan dan semakin lengkap atau bagus sebuah data yang disini saya gunakan adalah sebuah kumpulan teks maka semakin bagus juga model akan bekerja untuk melakukan segmentasi teks nya serta akurasi yang diharapkan semakin tinggi. Ada berbagai jenis model pipeline yang bisa kita gunakan untuk NLP tergantung kebutuhan ada Translator untuk menerjemahkan antar bahasa, qa untuk menjawab pertanyaan contoh penggunaannya ada di chtbot, ada classifier yang digunakan untuk menentukan apakah kalimatnya berisi segmentasi postitif atau negatif biasanya digunakan untuk analisis rating sebuah produk di marketplace berdasarkan ulasan pelanggan, ada summarizer untuk meringkas sebuah teks.
</div>
