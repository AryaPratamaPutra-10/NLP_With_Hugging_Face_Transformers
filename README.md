<h1 align="center"> NLP With Hugging Face Transformers </h1>
<p align="center"> Berisi tentang pipeline dari HuggingFace Transformers untuk keperluan NLP (Natural Language Processing) </h1>

<div align="center">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">
</div>

<h2 align="center"> Analisis </h2>
- Zero-Shot Classification
Merupakan jenis klasifikasi dengan metode Zero-Shot yang dimana metode ini mengklasifikasi teks ke dalam label yang diberikan sesuai dengan kategorinya dan semakin mendekati 1 berarti semakin akurat, metode ini mencoba menghubungkan konsep dengan hubungan kata - kata
- Jawaban akan pertanyaan yang dijawab oleh model tergantung dari konteks yang kita masukkan semakin relevan konteks yang kita masukkin semakin akurat model memberikan jawaban
- generator ("text-generation") dapat melakukan fungsi untuk melatih model untuk menghasilkan prediksi kata - kata yang logis dengan teks yang telah kita masukkin sebelumnya
- distilgpt2 adalah model yang bisa menghasilkan kalimat lanjutan dari kalimat yang kita masukkin dan kalimat yang dihasilkan juga berbeda - beda dan disini saya juga bisa menentukan maksimun token yang akan dihasilkan dan berapa banyak kalimat yang mau dihasilkan
- unmasker = pipeline("fill-mask") model ini dapat memprediksi kata yang bisa mengisi kalimat yang kosong dalam contoh yang saya buat saya memprediksi 3 kata yang mungkin bisa mengisi kekosongan kalimat berikut "in the future Artificial Intelligence will replace <mask> human."
- ner adalah fungsi yang dapat mengidentifikasi entitas di dalam text yang saya masukkin lalu mengelompokkan jenis entitas yang terdapat di dalam text
- "question-answering" merupakan fungsi yang dapat menjawab pertanyaan dari context yang kita berikan dan jawabannya akan sesuai context yang dimasukkan
- Classifier ("sentiment-analysis") adalah fungsi yang dapat menganalisa sentimen dari kalimat yang saya masukkin dan hasilnya akan diklasifikasikan menjadi label positive ataupu negatif dan apabila scorenya mendekati 1 semakin kuat sentiment nya positive
- Summarizer merupakan fungsi untuk meringkas teks dari konteks teks yang kita masukkin
- Translator merupakan fungsi untuk menerjemahkan bahasa dari teks dan bahasanya bisa kita masukkin di sini saya coba menerjemahkan teks bahasa indonesia lalu ditampilkan ke bahasa inggris 