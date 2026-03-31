# 📄 DisleksiBridge - Ürün Gereksinim Belgesi (PRD)

## 1. Ürün Vizyonu (Neyi, Neden Yapıyoruz?)
Disleksi eğitimi sadece okulda bitmez. Ancak ebeveynler, öğretmenlerin akademik dilini anlamakta zorlandıkları için evdeki süreci yönetemiyorlar. **DisleksiBridge**, bu iki taraf arasındaki "dil ve takip" bariyerini yapay zeka ile yıkan bir web platformudur.

## 2. Hedef Kitle (Kullanıcılar)
* **Öğretmen/Eğitmen:** Akademik bilgiyi giren, gelişimi izleyen kişi.
* **Ebeveyn:** AI tarafından sadeleştirilen talimatları uygulayan ve geri bildirim veren kişi.
* **Yönetici (Opsiyonel):** Okul veya kurum bazlı genel takibi yapan kişi.

## 3. Kullanıcı Hikayeleri (User Stories)
* **Öğretmen olarak;** sisteme teknik bir ödev girmek istiyorum ki veli ne yapacağını bilsin.
* **Ebeveyn olarak;** öğretmenin karmaşık notunu "bugün evde ne yapmalıyım?" şeklinde basitçe görmek istiyorum.
* **Ebeveyn olarak;** evdeki oyunun nasıl geçtiğini işaretlemek istiyorum ki öğretmen gelişimden haberdar olsun.
* **Öğretmen olarak;** haftalık grafikleri görüp çocuğun hangi alanda (örn: görsel hafıza) zorlandığını anlamak istiyorum.

## 4. Fonksiyonel Gereksinimler
### 4.1. Kayıt ve Giriş Sistemi
* Ebeveyn ve Öğretmen için ayrı giriş panelleri.
* Öğretmen, kendi sınıfındaki öğrencileri/velileri bir kod ile davet edebilmeli.

### 4.2. AI Destekli Ödev Motoru (Projenin Kalbi)
* **Girdi:** Metin kutusu (Öğretmen akademik notunu yazar).
* **İşlem:** Yapay Zeka (Gemini API) bu metni alır ve analiz eder.
* **Çıktı:** 1. Basitleştirilmiş "Halk Dili" talimatlar.
    2. "Evdeki malzemelerle 3 oyun" önerisi.

### 4.3. Gelişim Takip Paneli (Dashboard)
* Ebeveynin "Ödevi yaptık/Çok zorlandık" gibi geri bildirimlerini toplayan basit bir form.
* Bu verilerin öğretmene grafiklerle (Pasta dilimi, çizgi grafiği) sunulması.

## 5. Teknik Gereksinimler (Tech Stack)

| Katman | Teknoloji Önerisi | Neden? |
| :--- | :--- | :--- |
| **Frontend** | React.js / Tailwind CSS | Hızlı, modern ve mobil uyumlu tasarım için. |
| **Backend** | Node.js / Python | Yapay zeka entegrasyonu için en iyisi. |
| **AI Entegrasyonu** | Gemini API (Google) | Metinleri sadeleştirmek ve oyun üretmek için. |
| **Yayınlama** | Lovable / Netlify | Saniyeler içinde canlıya almak için. |

## 6. Tasarım ve Kullanıcı Deneyimi (UI/UX)
* **Renk Paleti:** Disleksi dostu fontlar (OpenDyslexic) ve gözü yormayan pastel renkler (Açık mavi, yumuşak sarı).
* **Mobil Uyumluluk:** Ebeveynler için "Responsive" (telefona uyumlu) tasarım.
* **Basitlik:** Ana sayfada dev bir "Bugünkü Ödevimiz" kartı.

## 7. Başarı Kriterleri (MVP)
Uygulamanın ilk versiyonunda şu 3 şey hat
