# Image-Processing

## Proje Açıklaması
Bu proje, *beyin tümörlerinin lokalizasyonunu* sağlamak amacıyla görüntü işleme tekniklerini kullanır. Medikal profesyonellerin doğru teşhis koymalarını desteklemeyi hedefler.

---

## Kullanılan Teknolojiler
- *C++*: Ana programlama dili
- *OpenCV*: Görüntü işleme kütüphanesi
- *NumPy*: Sayısal hesaplama ve veri işleme
- *Matplotlib*: Görselleştirme araçları

---

## Proje Dosya Yapısı
```plaintext
Image-Processing/
├── data/                        # Örnek MRI görüntüleri
├── src/                         # Kod dosyaları
│   ├── preprocess.py            # Görüntü ön işleme
│   ├── tumor_localization.py    # Tümör lokalizasyon algoritması
│   └── utils.py                 # Yardımcı fonksiyonlar
├── results/                     # Çıktı görüntüleri
├── README.md                    # Proje açıklaması
└── requirements.txt             # Gerekli kütüphaneler
