
# 🖊 Digit Recognizer - MNIST Sınıflandırma Projesi

Bu proje, el yazısı rakamları tanımak için derin öğrenme tekniklerine odaklanmaktadır. Model, MNIST veri seti kullanılarak geliştirilmiş ve %99.56 doğruluk oranı ile Kaggle yarışmasında ilk %5'te yer almıştır.

## 🔗 Kaggle Yarışması
[Digit Recognizer - Kaggle](https://www.kaggle.com/c/digit-recognizer)

## 🏆 Sonuçlar
- Test setinde %99.56 doğruluk elde edilmiştir.
- Yarışmada ilk %5'te yer almıştır.

## 📈 Model Geliştirme
- **CNN Mimarisi**: Basit bir CNN ile başlayıp daha derin mimarilere evrim geçirildi.
- **Düzenleme**: Aşırı uyumdan kaçınmak için Dropout ve Batch Normalization kullanıldı.
- **Veri Artırma**: Veri çeşitliliğini artırmak için döndürme, yakınlaştırma ve kaydırma teknikleri uygulandı.

## 🔧 Optimizasyonlar
- **Optimizatör ve Öğrenme Hızı**: Adam optimizatörü ve ReduceLROnPlateau kullanıldı.
- **Eğitim Parametreleri**: Stabilite için 30 epoch, 64 batch boyutu.
- **Özellik Çıkarımı**: Daha iyi özellik öğrenimi için Conv2D filtreleri artırıldı.
