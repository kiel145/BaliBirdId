# BaliBirdId
BirdID Bali is a computer vision project to identify bird species in Bali from images. It supports biodiversity monitoring by using public datasets and engaging users, such as tourists, to recognize local birds. The model focuses on common and vulnerable species.

# Latar Belakang Masalah

Bali merupakan salah satu destinasi wisata utama di Indonesia yang memiliki keanekaragaman hayati tinggi, termasuk berbagai spesies burung yang berperan penting dalam menjaga keseimbangan ekosistem. Burung juga dikenal sebagai indikator kesehatan lingkungan karena sensitivitasnya terhadap perubahan habitat.

Namun, meningkatnya aktivitas pariwisata berpotensi memberikan tekanan terhadap lingkungan alami, yang dapat memengaruhi populasi burung. Pemantauan populasi burung saat ini masih terbatas pada lembaga dan komunitas tertentu, sehingga cakupan data yang diperoleh belum optimal.

Di sisi lain, wisatawan sering mengambil foto burung selama berkunjung, tetapi data tersebut belum dimanfaatkan secara maksimal. Oleh karena itu, diperlukan pendekatan berbasis teknologi, seperti computer vision, untuk membantu mengidentifikasi spesies burung sekaligus mendukung pengumpulan data observasi secara lebih luas.

# Tujuan Project

Membangun model machine learning berbasis computer vision yang mampu mengklasifikasikan spesies burung di Bali secara akurat berdasarkan gambar.

# Output Project

Output dari project ini meliputi:

Model klasifikasi gambar yang telah dilatih
Evaluasi performa model menggunakan metrik klasifikasi
Dataset hasil kurasi dari iNaturalist dan Kaggle
(Opsional) Aplikasi berbasis web untuk identifikasi burung dari gambar

# Data

Dataset diperoleh dari beberapa sumber:

iNaturalist API → data observasi burung (gambar + metadata)
Kaggle Dataset → dataset tambahan untuk memperkaya data

Dataset mencakup:

Gambar burung
Label spesies burung
Variasi kondisi nyata (background, pencahayaan, sudut pengambilan

# Metodologi

Dalam project ini digunakan pendekatan image classification dengan deep learning.

Tahapan yang dilakukan:

Data Collection (API & Kaggle)
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Data Augmentation (jika digunakan)
Training model (CNN / Transfer Learning)
Model Evaluation
Pemilihan model terbaik

Model yang digunakan:

Convolutional Neural Network (CNN)
Transfer Learning (contoh: ResNet / EfficientNet)

Metric evaluasi yang digunakan:

Accuracy
Precision, Recall, F1-Score

# Tech Stack
Bahasa Pemrograman:
Python
Library yang digunakan:
NumPy
Pandas
TensorFlow / Keras atau PyTorch
Scikit-learn
Matplotlib
Seaborn

# Data Source:
iNaturalist API
Kaggle

# Referensi
iNaturalist: https://www.inaturalist.org
Kaggle Dataset: https://www.kaggle.com/datasets/sharansmenon/inatbirds100k

# Kesimpulan

Project ini berhasil membangun model klasifikasi gambar untuk mengenali spesies burung di Bali menggunakan pendekatan computer vision. Model mampu mengklasifikasikan beberapa spesies burung berdasarkan gambar dengan performa yang cukup baik.

Selain sebagai alat identifikasi, project ini juga berpotensi mendukung pengumpulan data observasi burung secara lebih luas melalui partisipasi pengguna. Dengan demikian, project ini tidak hanya memiliki nilai teknis.
