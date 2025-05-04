 ## 1. Pandas (Proses Data)
Pandas adalah library Python untuk manipulasi dan analisis data, terutama data berbentuk tabel (DataFrame).
Fungsi utama:
-Membaca data `(read_csv, read_excel)`.
-Menampilkan data awal `(head(), tail())`.
-Statistis deskriptif `(describe(), info())`.
-Pembersihan data `(missing values: fillna(), dropna())`.
-Manipulasi kolom dan baris `(groupby(), sort_values(), drop(), rename())`.

 ## 2. Matplotlib (Visualisasi Data)
Matplotlib digunakan untuk membuat grafik dari data.
#### Contoh penggunaan:
-Garis: `plt.plot()`
-Histogram: `plt.hist()`
-Bar chart:` plt.bar()`
-Scatter plot: `plt.scatter()`
-Menambahkan judul dan label:` plt.title(), plt.xlabel(), plt.ylabel()`

### 3. Naive Bayes (Klasifikasi Probabilistik)
Naive Bayes adalah algoritma klasifikasi berbasis teorema Bayes dengan asumsi independensi antar fitur.
Karakteristik:
-Cepat dan efisien untuk data besar.
-Cocok untuk teks (spam filter, analisis sentimen).
-Asumsi: fitur saling bebas (naive).
#### IMPLEMENTASI DI PYTHON
``` python
from sklearn.naive_bayes import GaussianNB
model = GaussianNB()
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
```
---

###  4. Decision Tree (Klasifikasi dan Regresi)
Decision Tree menggunakan struktur pohon untuk membuat keputusan berdasar fitur input.
Karakteristik:
-Mudah dipahami dan divisualisasikan.
-Bisa digunakan untuk klasifikasi dan regresi.
-Rentan terhadap overfitting jika tidak dipangkas.
#### IMPLEMETANSI DI PYTHON
``` python
from sklearn.tree import DecisionTreeClassifier
model = DecisionTreeClassifier()
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
```
---
#### VISUALISASI POHON
``` pyhton
from sklearn.tree import plot_tree
plot_tree(model)
```
----
