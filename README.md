# İHA Görüntülerinde Çoklu Sensör Destekli Zorlu Görüş Koşullarına Dayanıklı Nesne Tespiti ve Risk Farkındalığı Sistemi

Bu proje, **TÜBİTAK 2209-A** Üniversite Öğrencileri Araştırma Projeleri Destek Programı kapsamında geliştirilmektedir.

## 📌 Proje Özeti
İnsansız Hava Araçlarının (İHA) operasyonel süreçlerinde karşılaştığı sis, düşük ışık, gece, yağmur ve hareket bulanıklığı gibi zorlu çevresel koşullarda insan ve araç gibi kritik unsurların yüksek doğrulukla tespit edilmesi amaçlanmaktadır. Çalışmada, **VisDrone-DET, UAVid ve ACDC** veri setleri kullanılarak veri zenginleştirme ve domain adaptasyonu yöntemleri uygulanmakta; RGB optik kameralar ile çoklu sensör verileri harmanlanarak zorlu ortamlarda hedef tespiti sürdürülebilir kılınmaktadır. Ayrıca, tespit edilen nesnelerin konumları ve modelin güven skorları analiz edilerek operatöre kritik risk bölgelerini uyarı olarak sunan akıllı bir **durumsal farkındalık arayüzü** geliştirilmektedir.

## 🗂️ Kullanılan Veri Setleri
* **VisDrone-DET:** İHA perspektifinden çekilmiş nesne tespiti ve sınırlayıcı kutu etiketleri.
* **UAVid:** Piksel düzeyinde semantik segmentasyon etiketleri.
* **ACDC:** Sis, gece, yağmur ve kar koşullarındaki zorlu sahneler.

## 🛠️ Teknik Altyapı ve Yöntem
* **Yapay Zeka Motoru:** Ultralytics YOLO mimarisi ve çoklu sensör veri füzyon katmanları.
* **Çalışma Ortamı:** Google Colab (T4 GPU desteği) & PyTorch.
* **Risk Farkındalığı:** Düşük güven skorlu tespitlerin ve tehlikeli bölgelerin operatör arayüzünde (UI) filtrelenmesi ve görselleştirilmesi.

## 🚀 Kurulum ve Çalıştırma
Projedeki Jupyter Notebook dosyalarını Google Colab üzerinden açarak doğrudan çalıştırabilirsiniz:
1. Depodaki `.ipynb` dosyasını indirin veya Colab'da açın.
2. Çalışma zamanı türünü **T4 GPU** olarak ayarlayın.
3. Adım adım kodları çalıştırarak nesne tespiti testlerini gerçekleştirin.

## 📄 Lisans
Bu proje akademik ve araştırma amaçlı geliştirilmiştir.
