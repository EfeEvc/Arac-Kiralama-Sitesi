# EFE Rent A Car – Web Sitesi

Bu proje, **EFE Rent A Car** için geliştirilmiş basit ve modern bir araç kiralama web sitesidir. Tek sayfa (single-page) yapıda hazırlanmıştır ve **HTML, CSS ve temel JavaScript** kullanılmıştır. Kullanıcı dostu arayüz ve temel interaktif özellikler içerir.

---

## Özellikler

### 1. Ana Sayfa (Home)
- Firmanın sektördeki tecrübesi, araç filosu ve müşteri sayısı gibi istatistiklerin gösterimi.
- Müşteri yorumları (reviews) bölümü, yıldız derecelendirmeleriyle birlikte.
- Ana sayfadan doğrudan araç seçme butonu ile "Araçlar" bölümüne hızlı geçiş.

### 2. Araçlar (Cars)
- Kiralık araçların grid sistemi ile listelenmesi.
- Her araç için:
  - Görsel
  - Marka ve model
  - Günlük kiralama fiyatı
  - “Hemen Kirala” butonu
- Araç kiralama işlemi için basit bir rezervasyon bölümü:
  - Seçilen araç ismi ve fiyat hesaplama
  - Kiralama süresine göre toplam ödeme hesaplama
  - WhatsApp üzerinden rezervasyonu tamamlayabilme
- JavaScript ile kiralama seçimi ve toplam ödeme dinamik olarak hesaplanır.

### 3. Hakkımızda (About)
- Firma tarihçesi ve misyonu.
- Geniş araç filosu ve sağlanan hizmetler hakkında bilgi.
- Kullanıcıya güven veren tasarım ve mesajlar.

### 4. S.S.S (FAQ)
- Sıkça sorulan sorular, tıklanabilir başlıklarla gizli/açık metin gösterimi.
- Kiralama yaşı, ehliyet süresi ve fiyatlandırma ile ilgili bilgiler.

### 5. İletişim (Contact)
- Firma iletişim bilgileri (adres, telefon, e-posta).
- Google Maps iframe ile firmanın konumu gösterimi.

### 6. Tasarım ve Stil
- CSS değişkenleri ile ana renkler ve tema yönetimi:
  - Turuncu (`--primary`)
  - Koyu gri (`--dark`)
  - Açık gri (`--light`)
  - Yeşil (`--success`)
- Grid yapıları ile istatistikler, araçlar ve yorumlar düzenlenmiş.
- Responsive ve mobil uyumlu tasarım.
- Sticky header ve navigation menü.

### 7. JavaScript Fonksiyonları
- Sayfalar arası geçiş: `show(id)`
- FAQ aç/kapa işlevi: `toggleFaq(el)`
- Araç kiralama ve rezervasyon:
  - `rent(c,p)` → Seçilen aracı ve fiyatı ayarlar, rezervasyon bölümünü açar
  - `calc()` → Gün sayısına göre toplam ücreti hesaplar
  - `sendWhatsApp()` → Kullanıcı bilgilerini alıp WhatsApp üzerinden mesaj oluşturur

### 8. Footer
- Basit bir footer ile telif bilgisi ve firma adı belirtilmiştir.

---

## Kullanım

- Menüden bölümler arasında geçiş yapılabilir.
- Araçlar bölümünden seçilen araç kiralanabilir ve kiralama süresine göre toplam ödeme görüntülenir.
- Rezervasyon WhatsApp üzerinden tamamlanabilir.
- S.S.S bölümünde tıklanabilir sorular ile kullanıcı bilgilendirilir.
- İletişim sayfasında firma konumu ve iletişim bilgileri görüntülenir.

---

## Teknolojiler
- HTML5
- CSS3
- JavaScript (Vanilla)

---

## Lisans
Bu proje kişisel veya eğitim amaçlıdır. Ticari kullanım için izin gereklidir.
