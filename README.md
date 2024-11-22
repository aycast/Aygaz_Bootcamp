# Aygaz_Bootcamp
# Deprem Veri Seti Analizi Projesi

Bu proje, Türkiye'deki depremleri analiz etmek için hazırlanmıştır. Veri seti, 1919-2018 yılları arasındaki deprem kayıtlarını içermektedir. Proje, veri analizinden görselleştirmeye kadar çeşitli veri bilimi tekniklerini kullanarak anlamlı çıkarımlar yapmayı amaçlamaktadır.

---

## Table of Contents
1. [Proje Hakkında](#proje-hakkında)
2. [Veri Seti Detayları](#veri-seti-detayları)
3. [Kurulum ve Çalıştırma](#kurulum-ve-çalıştırma)
4. [Projede Yapılan İşlemler](#projede-yapılan-işlemler)
5. [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
6. [Sonuçlar ve Çıkarımlar](#sonuçlar-ve-çıkarımlar)

---

## Proje Hakkında

Bu projede, Türkiye'deki depremlerle ilgili çeşitli istatistiksel analizler gerçekleştirilmiştir. Amaç, depremlerin büyüklüklerine, lokasyonlarına ve zamanla nasıl değiştiğine dair bir anlayış geliştirmektir.

### Hedefler:
- Deprem verilerini anlamlı şekilde görselleştirmek.
- Veri setindeki eksik değerleri tespit etmek ve ele almak.
- Korelasyon analizleri ve diğer istatistiksel metrikleri kullanarak öngörüler sağlamak.

---

## Veri Seti Detayları

- **Kaynak**: Kaggle
- **Veri Seti Adı**: [Earthquakes in Turkey (1919-2018)](https://www.kaggle.com/datasets/hamzatanc/earthquakes-in-turkey-19192018)
- **Boyut**: ~6 MB
- **Sütunlar**:
  - `Date`: Deprem tarihi
  - `Latitude` ve `Longitude`: Depremin lokasyonu
  - `Magnitude`: Deprem büyüklüğü
  - `Depth`: Depremin derinliği

---

## Kurulum ve Çalıştırma

1. **Gereksinimler**:
   - Python 3.8+
   - Pandas, NumPy, Matplotlib, Seaborn, Missingno

2. **Bağımlılıkların Yüklenmesi**:
   ```bash
   pip install -r requirements.txt
