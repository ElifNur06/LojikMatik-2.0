# LojikMatik 2.0

LojikMatik, dijital mantık devrelerinin tasarımı, optimizasyonu ve analizi için geliştirilmiş profesyonel bir mühendislik aracıdır. Flutter framework kullanılarak modüler ve yüksek performanslı bir mimari ile geliştirilmiştir.

## 🚀 Temel Özellikler

LojikMatik, akademik ve profesyonel ihtiyaçları karşılamak üzere aşağıdaki modülleri içerir:

* **Gelişmiş Hesaplama Motoru:** `logic_engine.dart` üzerinde çalışan, Quine-McCluskey (QM) algoritması tabanlı analiz motoru. Minterm analizi, ikili dönüşüm ve 'Prime Implicant Chart' ile zorunlu terim seçimi (Essential PIs) süreçlerini eksiksiz uygular.
* **Dinamik Çizim Motoru:** `CustomPainter` ve `InteractiveViewer` bileşenleri ile devre şemalarını vektörel, yakınlaştırılabilir ve kaydırılabilir şekilde render eder.
* **Eğitimsel Çözüm Adımları:** "Adım Adım Çözüm" modülü ile QM algoritmasının tüm aşamaları (gruplama, birleştirme, temel asal çıkarımlar) şeffaf bir şekilde sunulur.
* **Karnaugh Haritası (K-Map):** 2, 3 ve 4 değişkenli mantıksal ifadeler için görsel analiz ve interaktif tablo desteği.
* **Tersine Mühendislik:** Doğruluk tablosu verilerini kullanarak mantıksal ifade ve devre sentezleme yeteneği.
* **Entegre (IC) Kütüphanesi:** 7400 serisi mantık entegreleri için hızlı pinout ve fonksiyon bilgisi.
* **Verilog HDL Sentezi:** Optimize edilmiş ifadeleri endüstri standardı Verilog HDL formatına otomatik dönüştürür.
* **PDF Raporlama:** Teknik raporları (doğruluk tabloları, K-Map, şema, çözüm adımları ve kod dahil) profesyonel PDF formatında dışa aktarır.

## 🛠 Teknik Mimari

* **Framework:** Flutter
* **Hesaplama:** Quine-McCluskey Algoritması
* **Görselleştirme:** Custom Painter & InteractiveViewer
* **İhracat:** `pdf` ve `printing` paketleri ile vektörel raporlama
* **Veri Yönetimi:** SharedPreferences

## 📱 Ekran Görüntüleri & Arayüz

Uygulama, `ResponsiveWrapper` yapısı sayesinde mobil cihazlardan geniş masaüstü ekranlarına kadar her ölçekte kusursuz bir kullanıcı deneyimi sunar. 6 ana sekme üzerinden modüler bir çalışma alanı sağlar:
1. Ana Sayfa (Hesaplama)
2. Tersine Mühendislik
3. Entegre Kütüphanesi
4. K-Map Viewer
5. Şema Görüntüleyici
6. Kayıtlı Projeler
<img width="420" height="741" alt="image" src="https://github.com/user-attachments/assets/b829f76e-e73f-48b2-b37a-b51b7c5daceb" />
<img width="417" height="742" alt="image" src="https://github.com/user-attachments/assets/982cde0e-1874-47aa-817c-a14af43443e8" />
<img width="418" height="744" alt="image" src="https://github.com/user-attachments/assets/6f470061-3622-4836-87b0-635c8e0d2484" />
<img width="419" height="742" alt="image" src="https://github.com/user-attachments/assets/88eecc4c-5f90-483e-b955-1f421b5b9832" />
<img width="417" height="742" alt="image" src="https://github.com/user-attachments/assets/f325efba-d9b5-4f79-92e3-1d0500cb8dc0" />
<img width="413" height="745" alt="image" src="https://github.com/user-attachments/assets/d724266a-1d68-4759-9c6a-6b384acf1a7d" />
<img width="418" height="739" alt="image" src="https://github.com/user-attachments/assets/bde2a0a2-0857-4224-93db-03ac67e9f2a8" />
<img width="414" height="742" alt="image" src="https://github.com/user-attachments/assets/12ffffaf-a75c-42d7-8b0f-855c28626579" />
<img width="414" height="741" alt="image" src="https://github.com/user-attachments/assets/ee45fef5-684a-47a5-b71b-9a8a1cdcfbdc" />
<img width="419" height="745" alt="image" src="https://github.com/user-attachments/assets/8538a4c8-3840-40a2-94bd-f5f903b83fa3" />
<img width="417" height="739" alt="image" src="https://github.com/user-attachments/assets/2e05f110-b6ad-427e-b2ba-137b9a5bafc6" />

## 💡 Monetizasyon
Uygulama, Google Mobile Ads (`RewardedAd` ve `InterstitialAd`) entegrasyonu ile kilitli içeriklerin (özellikle "Adım Adım Çözüm" ders notları) reklam izlenerek erişilebilir olmasını sağlayan bir model kullanır.

---
*Bu proje, dijital mantık tasarım süreçlerini hızlandırmak ve eğitimciler ile öğrencilere yardımcı olmak amacıyla geliştirilmiştir.*
