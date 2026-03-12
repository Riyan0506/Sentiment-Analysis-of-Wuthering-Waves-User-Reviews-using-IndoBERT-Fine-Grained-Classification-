🎮 Sentiment Analysis of Wuthering Waves User Reviews using IndoBERT (Fine-Grained Classification)

Proyek ini bertujuan untuk melakukan **analisis sentimen ulasan pengguna game Wuthering Waves** menggunakan model **IndoBERT** dengan pendekatan **fine-grained sentiment classification**.

Analisis ini dilakukan untuk memahami bagaimana persepsi pemain terhadap game **Wuthering Waves**, baik dari segi pengalaman bermain, performa game, maupun fitur yang tersedia. Dengan menggunakan model berbasis **Transformer**, sistem dapat mengklasifikasikan sentimen ulasan pengguna secara lebih akurat.

---

# 🎯 Objective

Tujuan dari proyek ini adalah:

* Menganalisis sentimen ulasan pemain **Wuthering Waves**
* Mengklasifikasikan sentimen menggunakan pendekatan **fine-grained sentiment**
* Mengimplementasikan model **IndoBERT untuk Natural Language Processing (NLP)**
* Mengevaluasi performa model dalam mengklasifikasikan sentimen pengguna

---

# 📂 Dataset

Dataset yang digunakan berisi **ulasan pengguna game Wuthering Waves** yang dikumpulkan dari platform distribusi aplikasi/game.

Isi dataset meliputi:

* **Review Text** → teks ulasan pengguna
* **Sentiment Label** → label sentimen
* **Rating (opsional)** → skor penilaian pengguna

Sentimen diklasifikasikan menggunakan **fine-grained sentiment**, misalnya:

* Very Negative
* Negative
* Neutral
* Positive
* Very Positive

Pendekatan ini memberikan analisis sentimen yang **lebih detail dibandingkan klasifikasi positif/negatif biasa**.

---

# 🛠️ Tools & Libraries

Proyek ini menggunakan beberapa teknologi berikut:

* **Python 3**
* **Google Colab / Jupyter Notebook**
* **Pandas**
* **NumPy**
* **PyTorch**
* **HuggingFace Transformers**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**

Model utama yang digunakan:

**IndoBERT**

Model ini merupakan model **Transformer berbasis BERT yang dilatih khusus untuk bahasa Indonesia**.

---

# 🔄 Workflow

Tahapan analisis pada proyek ini adalah sebagai berikut:

## 1️⃣ Data Collection

Mengumpulkan dataset ulasan pengguna **Wuthering Waves**.

## 2️⃣ Data Preprocessing

Tahap pembersihan data teks meliputi:

* Case Folding
* Cleaning text
* Stopword Removal
* Tokenization
* Text normalization

Preprocessing dilakukan untuk meningkatkan kualitas data sebelum digunakan oleh model NLP.

---

## 3️⃣ Tokenization

Dataset diproses menggunakan **IndoBERT Tokenizer** untuk mengubah teks menjadi format yang dapat dipahami oleh model Transformer.

---

## 4️⃣ Model Training

Model yang digunakan:

**IndoBERT**

Model dilatih untuk melakukan **klasifikasi sentimen fine-grained** pada ulasan pengguna.

---

## 5️⃣ Model Evaluation

Performa model dievaluasi menggunakan beberapa metrik, seperti:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Confusion Matrix**

Evaluasi ini digunakan untuk mengetahui seberapa baik model dalam mengklasifikasikan sentimen ulasan pengguna.

---

# 📊 Results

Hasil analisis menunjukkan bahwa model **IndoBERT mampu mengklasifikasikan sentimen ulasan pengguna dengan performa yang baik**.

Model dapat mengidentifikasi berbagai jenis sentimen pemain, mulai dari **sangat negatif hingga sangat positif**, sehingga memberikan gambaran yang lebih detail mengenai pengalaman pengguna terhadap game **Wuthering Waves**.

Visualisasi hasil analisis ditampilkan dalam bentuk:

* **Confusion Matrix**
* **Distribusi Sentimen**
* **Grafik Evaluasi Model**

---

# 📈 Example Visualization

Visualisasi distribusi sentimen pengguna terhadap game **Wuthering Waves**.

```
(Upload grafik atau confusion matrix dari notebook di sini)
```

Contoh cara menampilkan gambar di README:

```markdown
![Confusion Matrix](images/confusion_matrix.png)
```

---

# 💡 Skills Demonstrated

Beberapa keterampilan yang digunakan dalam proyek ini:

* Natural Language Processing (NLP)
* Sentiment Analysis
* Transformer Models
* IndoBERT Implementation
* Text Preprocessing
* Machine Learning Evaluation
* Data Visualization

---

# 📁 Project Structure

```
wuthering-waves-sentiment-analysis
│
├── dataset
│   └── wuwa_reviews.csv
│
├── notebook
│   └── Wuwa_PIfix.ipynb
│
├── images
│   └── confusion_matrix.png
│
└── README.md
```

---

# 🚀 How to Run

1️⃣ Clone repository

```bash
git clone https://github.com/username/wuthering-waves-sentiment-analysis.git
```

2️⃣ Install dependencies

```bash
pip install transformers torch pandas scikit-learn matplotlib seaborn
```

3️⃣ Jalankan notebook

```
Wuwa_PIfix.ipynb
```

Notebook dapat dijalankan menggunakan:

* **Jupyter Notebook**
* **Google Colab**

---

# 📌 Conclusion

Analisis sentimen menggunakan **IndoBERT dengan klasifikasi fine-grained** mampu memberikan pemahaman yang lebih mendalam mengenai persepsi pemain terhadap game **Wuthering Waves**.

Pendekatan ini dapat membantu:

* Mengidentifikasi aspek game yang disukai pemain
* Mengetahui masalah atau keluhan pengguna
* Memberikan insight bagi pengembang game untuk meningkatkan kualitas produk.

---

# 👨‍💻 Author

**Muhammad Riyan Maulana**
🎓 Universitas Gunadarma
📚 Information Systems Student

---

💡 Jika kamu mau, aku juga bisa bantu buat **3 bagian penting agar repo kamu terlihat seperti portfolio Data Scientist serius**, yaitu:

* ⭐ **README dengan tampilan seperti repository AI/NLP profesional**
* 📊 **diagram workflow penelitian (cocok untuk skripsi / publikasi)**
* 🎮 **GitHub README dengan banner gambar Wuthering Waves + AI theme** (biar terlihat keren ketika dibuka recruiter).
