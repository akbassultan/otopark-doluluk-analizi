# 🚗 Otopark Doluluk Analiz Sistemi (Görüntü İşleme)

Bu proje, Python ve OpenCV kütüphanesi kullanarak bir otopark görüntüsü üzerinden boş ve dolu park yerlerini tespit eden interaktif bir sistemdir. Kullanıcılar, park alanlarını fare ile sürükleyerek manuel olarak tanımlayabilir ve sistem bu alanları gerçek zamanlı olarak analiz eder.



## ✨ Öne Çıkan Özellikler

- **Dinamik Park Yeri Seçimi:** Sabit koordinatlar yerine, fare ile sürükle-bırak (Drag & Drop) yaparak her park yerini özel boyutlarda çizebilirsiniz.
- **Adaptif Eşikleme:** Seçilen alanın boyutuna (piksel alanı) göre farklı analiz eşikleri uygular (küçük alanlar için hassas, büyük alanlar için katı kurallar).
- **Görüntü İyileştirme:** CLAHE (Kontrast sınırlı adaptif histogram eşitleme) ve Gaussian Blur kullanarak düşük ışıkta veya gürültülü görüntülerde daha iyi sonuç verir.
- **Detaylı Raporlama:** Ekran üzerinde toplam kapasite, boş/dolu sayısı ve yüzde bazında doluluk oranını görselleştirir.

## 🛠️ Kullanılan Teknolojiler

- **Python 3.x**
- **OpenCV:** Görüntü işleme ve görselleştirme.
- **NumPy:** Matris işlemleri ve veri analizi.
- **Pickle:** Seçilen park yeri koordinatlarını yerel hafızaya kaydetme.
