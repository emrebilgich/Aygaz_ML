# Aygaz Machine Learning Bootcamp - Fake Job Posting Prediction

# Proje Açıklaması
Bu proje, Aygaz Makine Öğrenimi Bootcamp kapsamında sahte iş ilanlarını tahmin etmeyi amaçlayan bir makine öğrenimi modelinin geliştirilmesini hedeflemektedir. Kaggle'dan alınan Fake Job Posting Prediction veri seti kullanılarak, sahte iş ilanlarının tespiti için sınıflandırma modelleri oluşturulmuştur. Proje, iş ilanlarının belirli özelliklerine göre sahte olup olmadığını öngörmeyi amaçlar.

# Veri Seti
Fake Job Posting Prediction: Bu veri seti, iş ilanlarına ait başlık, şirket bilgileri, iş açıklaması, lokasyon, tam zamanlı/yarı zamanlı pozisyon gibi çeşitli özellikler içerir. Amaç, bu verilere dayanarak bir iş ilanının sahte olup olmadığını tahmin etmektir. Veri setine Kaggle üzerinden ulaşılabilir.

Veri seti şu sütunları içerir:

title: İlan başlığı

company: Şirket adı

location: İş yeri lokasyonu

employment_type: İstihdam türü (tam zamanlı, yarı zamanlı)

required_experience: İlanın gerektirdiği deneyim

fraudulent: Sahte (1) veya gerçek (0) olarak etiketlenmiş


# Kullanılan Teknikler
Bu projede aşağıdaki teknikler ve yöntemler kullanılmıştır:

Exploratory Data Analysis (EDA): Verinin analiz edilip, anomali ve eksik değerlerin incelenmesi

Veri Ön İşleme: Eksik verilerin işlenmesi, kategorik verilerin sayısallaştırılması (encoding)

Sınıflandırma Modelleri:
Lojistik Regresyon, 
Karar Ağaçları, 
Random Forest

Hiperparametre Optimizasyonu: Grid Search ve Random Search yöntemleri ile model performansını iyileştirme

Model Değerlendirme: Accuracy, Precision, Recall, F1-score gibi metriklerin kullanılması


# Kullanılan Kütüphaneler
Projede kullanılan temel Python kütüphaneleri:

pandas

numpy

scikit-learn

matplotlib

seaborn


# Proje Yapısı
Proje şu şekilde yapılandırılmıştır:

data/: Veri dosyaları

notebooks/: Jupyter Notebook dosyaları

scripts/: Python script dosyaları

README.md: Projenin açıklama dosyası


# Sonuçlar
Proje sonunda en iyi performans gösteren model Random Forest Classifier olmuştur. Modelin doğruluk oranı %97 olarak hesaplanmıştır. Ayrıca precision, recall ve F1-score değerleriyle modelin performansı detaylı olarak analiz edilmiştir.

# Gereksinimler
Projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:

Python 3

numpy

pandas

scikit-learn

matplotlib

seaborn


# Kaggle 

https://www.kaggle.com/code/yunusemrebilgic/jobs18-09-ml

https://www.kaggle.com/code/yunusemrebilgic/k-means-ml

# Lisans

Bu proje, Apache License 2.0 ile lisanslanmıştır.

