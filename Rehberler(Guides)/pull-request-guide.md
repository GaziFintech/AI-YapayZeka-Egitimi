# 📬 Pull Request (PR) Rehberi: Ödevini Onaya Gönder!

Kodlarını kendi branch'ine (dalına) yükledin, peki şimdi ne olacak? Şimdi, yaptığın çalışmaları "liderine" yani ana depoya teslim etme zamanı. Biz bu sürece **Pull Request (PR)** diyoruz.

---

## 🧐 Pull Request Nedir?
Pull Request, aslında şu demektir: *"Ben ödevimi bitirdim, kontrol etmeni ve eğer uygunsa ana projeye dahil etmeni istiyorum."* Bu sayede liderin senin kodlarını inceler, gerekirse yorum yapar ve onaylar.

---

## 🚀 Adım Adım PR Açma Süreci

### 1. Adım: Başlatma (Sarı Bant)
Dosyalarını yükleyip kaydettiğinde (Commit), GitHub genellikle sana sayfanın üstünde sarı bir bant gösterir. 
* Eğer bu bandı görüyorsan: **"Compare & pull request"** butonuna bas.
* Eğer görmüyorsan: Üst menüden **"Pull Request"** sekmesine tıkla ve yeşil **"New pull request"** butonuna bas.

> [!TIP]
> **Görünüm Rehberi:**
> ![Pull Request Sekmesi](https://github.com/GaziFintech/AI-YapayZeka-Egitimi/blob/main/assets/prbuton.png?raw=true)
> ![New PR Butonu](https://github.com/GaziFintech/AI-YapayZeka-Egitimi/blob/main/assets/prnew.png?raw=true)

---

### 2. Adım: Doğru Dalları (Branch) Seçme
PR ekranında iki tane kutucuk göreceksin. Burası çok önemli:
* **base repository:** Gazi-FinTech/AI-Modul-XX (Ana depo) | **base:** main
* **head repository:** senin-ismin/AI-Modul-XX (Senin kopya) | **compare:** senin-adin-soyadin

> **Kontrol Et:** "Able to merge" (Birleştirilebilir) yazısını ve yeşil onay işaretini gördüğünden emin ol.

![Doğru Branch Seçimi](https://github.com/GaziFintech/AI-YapayZeka-Egitimi/blob/main/assets/prbranches.png?raw=true)

---

### 3. Adım: Teslim Formunu Doldurma
Butona bastığında karşına hazır bir şablon gelecek. Bu formu doldurmak hem senin takibini hem de liderinin incelemesini kolaylaştırır:
* **Başlık:** `[ÖDEV] - Adın Soyadın - Modül No` şeklinde bir başlık at.
* **Açıklama:** Şablondaki soruları yanıtla (Neleri bitirdin? Hangi konuda zorlandın?).

![PR Formu Doldurma](https://github.com/GaziFintech/AI-YapayZeka-Egitimi/blob/main/assets/prformu.png?raw=true)

---

### 4. Adım: Teslimi Tamamla
Her şey tamamsa, yeşil **"Create pull request"** butonuna bas. Artık top liderinde! 🎾

![Create PR Onay](https://github.com/GaziFintech/AI-YapayZeka-Egitimi/blob/main/assets/crateprbuton.png?raw=true)

---

## 👀 PR Gönderdikten Sonra Ne Olur?

1. **İnceleme (Review):** Liderin kodlarını satır satır inceler.
2. **Yorumlar:** Eğer düzeltilmesi gereken bir yer varsa, liderin kodunun yanına yorum bırakır. 
   * *Not:* Yorum gelirse panik yapma! Sadece kodunu düzeltip tekrar "Commit" (kaydet) yapman yeterli, PR otomatik olarak güncellenir.
3. **Onay (Approve):** Her şey harikaysa liderin PR'ını onaylar ve **"Merge"** (birleştirme) işlemini yapar.
4. **Kapanış:** Tebrikler! Projen artık Gazi FinTech'in resmi arşivinde yerini aldı. 🎉

---

## ⚠️ Dikkat: PR Açarken Yapılan En Büyük Hata!
**Kendi profilindeki "main" dalından PR açmaya çalışmak.** Lütfen her zaman kendi oluşturduğun `ad-soyad` dalını (branch) seçtiğinden emin ol. Aksi takdirde liderin kimin ödevini kontrol ettiğini anlamakta zorlanabilir.

**Takıldın mı?** Bir sorun yaşarsan [Gazi FinTech Discussions](https://github.com/orgs/GaziFintech/discussions) kısmından sormaktan çekinme!

---
*Gazi Finansal Teknolojiler Topluluğu - Proje Ekibi Lideri Arif Furkan Aytekin*
