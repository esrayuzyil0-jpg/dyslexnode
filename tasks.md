
###  1. Adım: Hazırlık ve Temel Kurulum
- [ ] Proje klasör yapısını oluştur (index.html, style.css, script.js).
- [ ] Tailwind CSS kütüphanesini projeye dahil et.
- [ ] **Erişilebilirlik:** OpenDyslexic fontunu projeye entegre et ve varsayılan font olarak ayarla.
- [ ] **Renk Paleti:** Arka planı disleksi dostu olan "krem/açık sarı" (#FFFDD0) tonlarında ayarla.

###  2. Adım: Ana Arayüz (UI) Tasarımı
- [ ] Uygulama girişinde "Öğretmen Girişi" ve "Veli Girişi" seçeneklerini sunan bir karşılama ekranı yap.
- [ ] Navigasyon çubuğunu (Navbar) oluştur ve "dyslexnode" logosunu ekle.
- [ ] Responsive (mobil uyumlu) tasarım ayarlarını tamamla.

###  3. Adım: Öğretmen Paneli Geliştirme
- [ ] Öğretmenlerin teknik notlarını girebileceği geniş bir metin alanı (textarea) oluştur.
- [ ] "Veli İçin Basitleştir" butonu ekle.
- [ ] Metin işlenirken görünecek bir "Yükleniyor..." animasyonu (spinner) ekle.

###  4. Adım: AI Entegrasyonu (Gemini API)
- [ ] Google AI Studio üzerinden alınan API anahtarını güvenli bir şekilde bağla.
- [ ] **System Prompt Hazırla:** Gemini'ye "Sen bir disleksi uzmanısın, bu teknik metni bir velinin evde çocukla yapabileceği 3 dakikalık basit bir oyuna dönüştür" talimatını ver.
- [ ] API'den gelen basitleştirilmiş metni ekranda göstermek için bir sonuç alanı oluştur.

###  5. Adım: Veli Paneli ve Geri Bildirim
- [ ] Velilerin basitleştirilmiş ödevleri göreceği "Günlük Görev Paneli"ni tasarla.
- [ ] Görevlerin yanına "Tamamlandı" onay kutuları ekle.
- [ ] Velinin gün sonu notu bırakabileceği bir "Geri Bildirim" kutusu yap.

###  6. Adım: Veri Analizi ve Sentez (Gelişmiş AI)
- [ ] Veliden gelen geri bildirimleri (örn: "b-d harflerini karıştırdı") Gemini API'ye gönder.
- [ ] AI'nın bu verileri analiz edip öğretmene "Haftalık Özet Rapor" sunmasını sağla.

### 7. Adım: Test ve Yayınlama
- [ ] Farklı ekran boyutlarında (mobil/tablet/desktop) testler yap.
- [ ] Uygulamayı Lovable veya Netlify üzerinden yayınla.
- [ ] Projenin canlı linkini GitHub `README.md` dosyasına ekle.
