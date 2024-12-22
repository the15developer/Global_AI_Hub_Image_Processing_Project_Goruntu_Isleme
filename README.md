# Global_AI_Hub_Image_Processing_Project

Proje Özeti

Bu projede hayvan türlerinden oluşan bir veri seti üzerinde Convolutional Neural Network (CNN) model eğitilmektedir. Görüntülerin renk manipülasyonları ve beyaz dengeleme uygulamalarıyla da modelin doğruluk oranları test edilmektedir. Model, başlangıçta orijinal test seti ile test edilip doğruluğu ölçülmüştür, ardından manipülasyonlar (üç farklı renk değişikliği) yapılmış ve modelin performansı tekrar test edilmiştir. Son olarak, beyaz dengeleme algoritması uygulanarak manipüle edilmiş test seti üzerinde doğruluk oranı tekrar hesaplanmıştır.

Kullanılan Kütüphaneler
Bu projede aşağıdaki Python kütüphaneleri kullanılmıştır:

TensorFlow: Derin öğrenme modeli eğitimi ve tahminleri için kullanıldı.
Keras: TensorFlow üzerine inşa edilen derin öğrenme kütüphanesi ile modelin oluşturulması ve eğitilmesi sağlandı.
OpenCV: Görüntü işleme ve manipülasyon (renk dengeleme ve beyaz dengeleme) işlemleri için kullanıldı.
NumPy: Matematiksel hesaplamalar ve veri işleme için kullanıldı.
Scikit-learn: Doğruluk hesaplaması ve diğer metriklerin değerlendirilmesi için kullanıldı.

Yapılan İşlemler

Görüntü Manipülasyonu: Veri setindeki her bir görsel üzerine üç farklı renk manipülasyonu uygulandı. Bu manipülasyonlar, modelin görsel çeşitliliği ile daha iyi genelleme yapabilmesi amacıyla yapıldı.

Beyaz Dengeleme: Manipülasyon sonrası renk dengeleme ve beyaz dengeleme algoritmaları uygulandı. Beyaz dengeleme, görüntülerdeki renk bozulmalarını düzeltmek ve görselin daha doğal görünmesini sağlamak amacıyla kullanıldı.

Model Eğitimi: Model, başlangıçta orijinal veri setiyle eğitildi ve ardından manipüle edilmiş veri setleriyle de test edildi. Modelin performansı her adımda ölçülüp, manipülasyonların model doğruluğuna etkisi incelendi.

Başarı Değerlendirmesi: Her bir test setinin doğruluğu hesaplandı. Sonuçlar karşılaştırıldı ve modelin renk manipülasyonlarına karşı dayanaklılığı değerlendirildi.

Sonuçlar
Projede kullanılan test setlerine göre doğruluk oranları:

Orijinal Test Seti: %68 doğruluk
Manipüle Edilmiş Test Seti: %9.47 doğruluk
Beyaz Dengeleme Uygulanan Test Seti: %10.32 doğruluk
Elde edilen bu sonuçlar, modelin renk manipülasyonlarına karşı oldukça hassas olduğunu ve performansının iyileştirilmesi gerektiğini göstermektedir.

Çözüm Yolları
Aşağıdaki çözüm yolları önerilmektedir:

Veri Artırma (Data Augmentation): Daha fazla veri manipülasyonu ile modelin genelleme kapasitesi artırılabilir.
Transfer Öğrenme: Önceden eğitilmiş modeller kullanılarak modelin performansı artırılabilir.
Model Güncellemeleri: Derin öğrenme modelinin mimarisi değiştirilerek daha güçlü bir yapı kurulabilir.

