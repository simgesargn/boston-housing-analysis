# Boston Housing Veri Analizi

Bu proje, Boston Housing veri seti kullanılarak veri analizi ve görselleştirme adımlarını içermektedir. Eksik veriler doldurulmuş, bazı değişkenlerin ev fiyatlarıyla ilişkisi incelenmiştir.

---

## Dosyalar

- `boston_housing_analysis.ipynb` → Ana analiz dosyası
- `HousingData.csv` → Veri seti
- `cleaned_boston_housing.csv` → Temizlenmiş veri seti (çalışma sonunda oluşturulmuştur)

---

## Kullanılan Kütüphaneler

```python
import pandas as pd  
import numpy as np  
import matplotlib.pyplot as plt  
import seaborn as sns


Yapılanlar
Veri seti yüklendi

Eksik veriler medyan ile dolduruldu

Temel istatistiksel bilgiler incelendi

İki özgün grafik ile veri görselleştirildi

Temiz veri seti .csv olarak dışa aktarıldı
