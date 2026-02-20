# 🤖 Modül 2: Klasik Makine Öğrenmesi - Detaylı Müfredat

Bu doküman; Makine Öğrenmesi temelleri, Regresyon, Sınıflandırma, Topluluk (Ensemble) yöntemleri ve Denetimsiz Öğrenme başlıklarından oluşan **Modül 2**'nin kaynak matrisini ve haftalık dökümünü içerir.

---

## 🗺️ Kaynak ve Müfredat Matrisi

Aşağıdaki tablo, öğrenim sürecinizdeki ana kaynakların hangi ML alanlarını kapsadığını göstermektedir. Matematiksel temeller için birleşik hücreler kullanılmıştır.

<table>
  <thead>
    <tr>
      <th>Kategori</th>
      <th>Konu Başlığı</th>
      <th align="center">1. Giriş ve Ön İşleme</th>
      <th align="center">2. Regresyon Modelleri</th>
      <th align="center">3. Sınıflandırma Modelleri</th>
      <th align="center">4. Ensemble & Unsupervised</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4"><b>Kaynaklar</b></td>
      <td>İnternet Sitesi</td>
      <td align="center"><a href="https://scikit-learn.org/stable/getting_started.html">Scikit-Learn Guide</a></td>
      <td align="center"><a href="https://www.statmethods.net/stats/regression.html">Quick-R: Regression</a></td>
      <td align="center"><a href="https://ml-cheatsheet.readthedocs.io/en/latest/logistic_regression.html">ML Cheatsheet</a></td>
      <td align="center"><a href="https://xgboost.readthedocs.io/en/stable/">XGBoost Docs</a> / <a href="https://scikit-learn.org/stable/unsupervised_learning.html">Clustering</a></td>
    </tr>
    <tr>
      <td>Medium / GfG</td>
      <td colspan="4" align="center"><a href="https://towardsdatascience.com/machine-learning/home">Towards Data Science: Comprehensive ML Pillars</a></td>
    </tr>
    <tr>
      <td>Youtube</td>
      <td align="center">StatQuest - ML Basics</td>
      <td colspan="2" align="center">Andrew Ng - Machine Learning Specialization</td>
      <td align="center">Krish Naik - Ensemble Techniques</td>
    </tr>
    <tr>
      <td>Eğitim Serisi</td>
      <td colspan="4" align="center">Coursera: Machine Learning by Stanford / Kaggle Learn: Intermediate Machine Learning</td>
    </tr>
    <tr>
      <td colspan="2"><b>Alıştırmalar</b></td>
      <td align="center">Preprocessing Lab (Sklearn)</td>
      <td align="center">Linear Reg. From Scratch</td>
      <td align="center">Classification Challenges</td>
      <td align="center">K-Means Implementation</td>
    </tr>
    <tr>
      <td colspan="2"><b>Final Projesi</b></td>
      <td colspan="4" align="center"><b>Uçtan Uca Tahminleme Modeli ve Model Değerlendirme Raporu</b></td>
    </tr>
  </tbody>
</table>

---

## 📋 Alt Başlık Detayları

Modül 2 kapsamında hakim olmanız gereken teknik detaylar aşağıdadır:

### ⚙️ 1. Giriş, Temeller ve Ön İşleme (6-1 ile 7-11 arası)
* **Kavramlar:** Denetimli/Denetimsiz öğrenme farkı, Overfitting ve Underfitting analizi.
* **Ön İşleme:** Feature scaling (Standardization/Normalization), One-hot encoding ve Label encoding.
* **Seçim:** Feature selection teknikleri ve Boyut azaltma (Dimensionality Reduction) mantığı.

### 📈 2. Supervised Learning - Regresyon (8-1 ile 8-4 arası)
* **Lineer & Polinomial:** En küçük kareler (Least Squares) yöntemi ve dereceli azalış (Gradient Descent) algoritması.
* **Matematik:** Maliyet Fonksiyonu ($J(\theta)$) hesaplamaları.
* **Düzenlileştirme:** Ridge ($L2$) ve Lasso ($L1$) regularization ile model karmaşıklığı yönetimi.
* **Lojistik:** Sigmoid fonksiyonu ve olasılıksal sınıflandırma temelleri.

### 🎯 3. Supervised Learning - Sınıflandırma (9-1 ile 9-4 arası)
* **Algoritmalar:** k-NN (Mesafe metrikleri), Karar Ağaçları (Gini/Entropy) ve SVM (Hyperplane/Kernel trick).
* **Olasılık:** Bayes Teoremi ve Naive Bayes sınıflandırıcıları.
* **Uygulama:** Her algoritmanın Scikit-learn implementasyonu ve hiperparametre optimizasyonu.

### 🌲 4. Ensemble Methods & Unsupervised Learning (10-1 ile 12-10 arası)
* **Ensemble:** Bagging (Random Forest) ve Boosting (XGBoost, LightGBM, CatBoost) farkları.
* **Unsupervised:** K-means clustering (Sıfırdan kodlama), Hierarchical clustering ve PCA.
* **Değerlendirme:** Confusion Matrix, Precision/Recall, F1-Score ve ROC-AUC analizi.

---
> **Lider Notu:** Modül 2'nin en büyük meydan okuması, algoritmaların matematiksel ispatlarını anlamaktır. Sadece kütüphane çağırmakla yetinmeyin!
