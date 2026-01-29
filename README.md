Image Classification using CNN (Basic Level)
# Image Classification using CNN (Basic Level)

Bu proje, temel seviyede bir Convolutional Neural Network (CNN) kullanarak
görüntü sınıflandırma mantığını öğrenmek amacıyla hazırlanmıştır. Çalışma,
bilgisayarlı görü alanındaki temel kavramları uygulamalı olarak göstermeyi hedefler.

## Proje Amacı
Görüntülerden anlamlı özellikler çıkararak sınıflandırma yapmak, yapay zekâ
uygulamalarının önemli bir parçasıdır. Bu projede amaç, basit bir CNN mimarisi
kurarak eğitim ve tahmin sürecinin nasıl çalıştığını kavramaktır.

## Kullanılan Teknolojiler
- Python
- TensorFlow
- Keras
- OpenCV

## Proje Dosyaları


train_model.py -> CNN modelinin oluşturulması ve derlenmesi


## Model Yapısı
Model; evrişim (convolution), havuzlama (pooling) ve tam bağlı (dense) katmanlardan
oluşmaktadır. Bu yapı sayesinde görüntülerden temel özellikler çıkarılarak
sınıflandırma işlemi gerçekleştirilir.

## Çalışma Mantığı
Görüntüler modele belirli bir boyutta verilerek eğitim süreci başlatılır.
Eğitim sırasında doğruluk ve kayıp değerleri takip edilir. Proje, daha gelişmiş
veri setleri ve model mimarileri için bir başlangıç niteliğindedir.

## Notlar
Bu proje eğitim ve staj amaçlıdır. Gerçek dünya uygulamalarında daha büyük veri
setleri, veri artırma teknikleri ve daha derin model mimarileri kullanılabilir.
