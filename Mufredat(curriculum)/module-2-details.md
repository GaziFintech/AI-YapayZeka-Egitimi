# 🤖 Modül 2: Klasik Makine Öğrenmesi - Detaylı Müfredat

Bu doküman, müfredatın 6. bölümünden 12. bölümüne kadar uzanan Klasik Makine Öğrenmesi sürecini kapsamaktadır. Her bölüm için özel kaynaklar ve alıştırmalar satır bazlı olarak düzenlenmiştir.

---

## 🗺️ Kaynak ve Müfredat Matrisi (Bölüm 6 - 12)

Aşağıdaki tablo, öğrenim sürecinizdeki ana kaynakların hangi bölümleri kapsadığını göstermektedir.

<table>
  <thead>
    <tr>
      <th>No</th>
      <th>Bölüm Adı</th>
      <th>İnternet Sitesi</th>
      <th>Medium / GfG</th>
      <th>Youtube</th>
      <th>Alıştırmalar</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><b>6</b></td>
      <td>Makine Öğrenmesine Giriş</td>
      <td><a href="https://scikit-learn.org/stable/preface.html">Sklearn Intro</a></td>
      <td><a href="https://medium.com/topic/machine-learning">ML Basics</a></td>
      <td>StatQuest: ML Basics</td>
      <td>Kavramsal Test</td>
    </tr>
    <tr>
      <td align="center"><b>7</b></td>
      <td>ML Temelleri (Ön İşleme)</td>
      <td><a href="https://scikit-learn.org/stable/modules/preprocessing.html">Preprocessing Guide</a></td>
      <td><a href="https://www.geeksforgeeks.org/data-preprocessing-machine-learning-python/">GfG Preprocessing</a></td>
      <td>Krish Naik: Preprocessing</td>
      <td>Scaling & Encoding Lab</td>
    </tr>
    <tr>
      <td align="center"><b>8</b></td>
      <td>Supervised Learning - Regresyon</td>
      <td><a href="https://ml-cheatsheet.readthedocs.io/en/latest/linear_regression.html">Reg. Cheatsheet</a></td>
      <td><a href="https://towardsdatascience.com/linear-regression-detailed-view-ea73175f5950">Linear Reg. Detail</a></td>
      <td>Andrew Ng: Regression</td>
      <td><b>Sıfırdan (Scratch) Kodlama</b></td>
    </tr>
    <tr>
      <td align="center"><b>9</b></td>
      <td>Supervised Learning - Sınıflandırma</td>
      <td><a href="https://scikit-learn.org/stable/modules/tree.html">Decision Trees</a></td>
      <td><a href="https://www.geeksforgeeks.org/classification-in-machine-learning/">Classification Guide</a></td>
      <td>StatQuest: SVM & Trees</td>
      <td><b>Sıfırdan (Scratch) k-NN</b></td>
    </tr>
    <tr>
      <td align="center"><b>10</b></td>
      <td>Ensemble Methods</td>
      <td><a href="https://xgboost.readthedocs.io/">XGBoost Docs</a></td>
      <td><a href="https://medium.com/tag/ensemble-learning">Ensemble Mastery</a></td>
      <td>Corey Schafer: Random Forest</td>
      <td>XGBoost vs RF Lab</td>
    </tr>
    <tr>
      <td align="center"><b>11</b></td>
      <td>Unsupervised Learning</td>
      <td><a href="https://scikit-learn.org/stable/modules/clustering.html">Clustering Guide</a></td>
      <td><a href="https://www.geeksforgeeks.org/clustering-in-machine-learning/">GfG Clustering</a></td>
      <td>Sentdex: PCA</td>
      <td><b>Sıfırdan (Scratch) K-Means</b></td>
    </tr>
    <tr>
      <td align="center"><b>12</b></td>
      <td>Model Değerlendirme ve Seçimi</td>
      <td><a href="https://scikit-learn.org/stable/modules/model_evaluation.html">Metrics Guide</a></td>
      <td><a href="https://towardsdatascience.com/metrics-to-evaluate-your-machine-learning-algorithm-f1043830c5c8">Evaluation Metrics</a></td>
      <td>StatQuest: ROC-AUC</td>
      <td>Hyperparameter Tuning Lab</td>
    </tr>
  </tbody>
</table>

---

## 📋 Teknik Alt Başlıklar (Sıralı Müfredat)



### 6. Makine Öğrenmesine Giriş
* **6-1-1.** Makine öğrenmesi nedir?
* **6-1-2.** Denetimli vs Denetimsiz öğrenme teorisi.
* **6-1-4.** Eğitim, doğrulama ve test kümeleri mantığı.
* **6-2-1.** Lineer Regresyon ve Multiple Lineer Regresyon giriş.

### 7. Makine Öğrenmesi Temelleri
* **7-1-3.** Overfitting ve underfitting tespiti.
* **7-1-4.** Bias-variance tradeoff dengesi.
* **7-2-1.** Feature scaling (normalization, standardization) teknikleri.
* **7-2-2.** Veri kodlama (one-hot, label encoding).

### 8. Supervised Learning - Regresyon
* **8-1-1.** En küçük kareler (least squares) matematiksel temeli.
* **8-1-2.** Gradient descent algoritması işleyişi.
* **8-1-3.** **Sıfırdan Python implementasyonu (Kütüphanesiz).**
* **8-3-1.** $L1$ (Lasso) ve $L2$ (Ridge) regularization farkları.

### 9. Supervised Learning - Sınıflandırma
* **9-1-1.** Mesafe metrikleri (Euclidean, Manhattan).
* **9-2-1.** Information gain ve entropy hesaplamaları.
* **9-3-2.** Kernel trick matematiksel altyapısı (SVM).
* **9-4-1.** Bayes Teoremi ve olasılıksal sınıflandırma.

### 10. Ensemble Methods
* **10-1-1.** Bootstrap sampling ve Bagging mantığı.
* **10-1-4.** **Sıfırdan Random Forest implementasyonu.**
* **10-2-2.** Gradient Boosting ve XGBoost/LightGBM kullanımı.

### 11. Unsupervised Learning
* **11-1-1.** K-means algoritması ve yakınsama (convergence).
* **11-1-5.** **Sıfırdan k-means implementasyonu.**
* **11-2-1.** PCA (Principal Component Analysis) ve Eigenvalue hesaplamaları.

### 12. Model Değerlendirme ve Seçimi
* **12-1-1.** Accuracy, Precision, Recall ve F1-Score metrikleri.
* **12-1-2.** ROC curve ve AUC alanı analizi.
* **12-2-1.** Grid Search ve Random Search ile hiperparametre optimizasyonu.

---
> **Önemli:** Modül 2 projelerinizi teslim ederken "Sıfırdan Kodlama" (Scratch) bölümlerine öncelik veriniz.
---
