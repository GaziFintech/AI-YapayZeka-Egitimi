# 🛠️ Geliştirme Ortamı Kurulum Rehberi (Environment Setup)

Yapay zeka ve veri bilimi projeleri geliştirmek için tek bir "doğru" yol yoktur. İster hiçbir şey kurmadan tarayıcı üzerinden çalış, istersen bilgisayarını profesyonel bir yazılım üssüne çevir. İşte seçeneklerin:

---

## ☁️ 1. Bulut Tabanlı Çözümler (Kurulum Gerektirmez)

Eğer bilgisayarın düşük donanımlıysa veya kurulumla vakit kaybetmek istemiyorsan bu iki seçenek senin için en iyisidir.

### 🟡 Google Colab
Google tarafından sunulan, tarayıcı üzerinden çalışan ücretsiz bir Jupyter Notebook hizmetidir.
* **Avantajı:** Ücretsiz GPU (Ekran Kartı) desteği sağlar (Derin öğrenme için kritik).
* **Nasıl Kullanılır?** [colab.research.google.com](https://colab.research.google.com/) adresine Google hesabınla giriş yapman yeterli.
* **Kayıt:** Dosyaların doğrudan Google Drive'ına kaydedilir.

### 🔵 Kaggle Kernels
Dünyanın en büyük veri bilimi topluluğu olan Kaggle'ın sunduğu çalışma ortamıdır.
* **Avantajı:** Veri setlerine çok hızlı erişim sağlar ve portfolyonu doğrudan Kaggle'da sergilemene imkan tanır.
* **Nasıl Kullanılır?** [kaggle.com](https://kaggle.com/) üzerinde bir hesap aç ve "Code" sekmesinden yeni bir Notebook oluştur.

---

## 💻 2. Yerel Kurulumlar (Profesyonel Çalışma)

Kendi bilgisayarında, internete bağlı olmadan ve dosyalarını yerel olarak yönetmek istiyorsan bu yolu izlemelisin.

### 🟢 Anaconda & Jupyter Notebook
Veri bilimi dünyasının standart paket yönetim sistemidir.
1. [Anaconda Dağıtımı](https://www.anaconda.com/download)'nı indir ve kur.
2. Kurulum bittikten sonra **Anaconda Navigator**'ı aç.
3. İçindeki **Jupyter Notebook** veya **JupyterLab**'i "Launch" diyerek çalıştır.
* **Not:** Anaconda kurduğunda Python, Pandas, NumPy gibi kütüphaneler otomatik olarak yüklü gelir.

### 🔵 Visual Studio Code (VS Code)
Dünyanın en popüler kod editörüdür. Sadece Python değil, tüm diller için kullanılır.
1. [code.visualstudio.com](https://code.visualstudio.com/) adresinden indir ve kur.
2. Sol taraftaki "Extensions" (Eklentiler) simgesine tıkla.
3. **"Python"** ve **"Jupyter"** eklentilerini aratıp yükle.
* **Avantajı:** Profesyonel yazılım geliştirme hissi verir, GitHub ile mükemmel entegre olur.

---

## 📦 3. Kütüphane Kurulumu (Kritik Adım)

Eğer Anaconda kullanmıyorsan (sadece VS Code veya saf Python kurduysan), eğitim boyunca kullanacağımız kütüphaneleri terminale/komut satırına şu kodu yazarak yüklemelisin:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

## 🎯 Hangisini Seçmeliyim?

Hangi ortamın sana en uygun olduğuna karar veremediysen bu tablo sana yol gösterecek. İlgili butona tıklayarak hemen başlayabilirsin:

| Durum | Tavsiye Edilen | Hemen Dene / İndir |
| :--- | :--- | :---: |
| **Hızlıca başlamak istiyorum** | Google Colab | [![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/) |
| **Bilgisayarım çok ısınıyor/yavaş** | Google Colab | [![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://colab.research.google.com/) |
| **Kaggle yarışmalarına katılacağım** | Kaggle Kernels | [![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/) |
| **Profesyonel bir temel atmak istiyorum** | VS Code / Anaconda | [![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/) <br> [![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com/) |

---

> [!IMPORTANT]
> **Yardım mı lazım?** Kurulumda bir hata alırsan ekran görüntüsü alıp [Discussions](https://github.com/orgs/GaziFintech/discussions) kısmında paylaşabilirsin. Gazi FinTech ekibi her zaman yanında! 🚀

---
*Gazi Finansal Teknolojiler Topluluğu - Proje Ekibi Lideri Arif Furkan Aytekin*
