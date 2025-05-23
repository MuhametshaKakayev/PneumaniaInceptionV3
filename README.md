Pneumonia Detection with InceptionV3 using Chest X-ray Images

Bu proje, Chest X-ray Pneumonia veri setini kullanarak InceptionV3 önceden eğitilmiş modelinden yararlanarak zatürre (pneumonia) hastalığını tespit etmeyi amaçlamaktadır.
Proje Özeti

    Veri Seti: Kaggle’dan indirilen chest X-ray görüntüleri. Veri seti; NORMAL ve PNEUMONIA olmak üzere iki sınıfa ayrılmıştır.

    Veri İşleme: Eğitim seti dengelenmiş, ayrıca eğitim/validasyon/test olarak ayrılmıştır.

    Model: Transfer öğrenme ile InceptionV3 tabanlı derin sinir ağı.

    Eğitim: Veri artırma (augmentation) ve erken durdurma (early stopping) gibi tekniklerle model optimize edilmiştir.

    Değerlendirme: Modelin doğruluğu, precision, recall, F1 skoru ve ROC-AUC metriği hesaplanmıştır.

    Görselleştirme: Grad-CAM yöntemiyle modelin karar verme sürecindeki dikkat alanları görselleştirilmiştir.

Kullanım

    Veri seti Kaggle API ile indirilir ve uygun klasör yapısına kopyalanır.

    Model eğitilir ve test edilir.

    Test görüntülerinden rastgele seçilerek tahmin ve Grad-CAM ısı haritası oluşturulur.

    Performans metrikleri ve ROC eğrisi görselleştirilir.

Geliştirme, eğitim sonuçları ve örnek görseller için kodları inceleyebilirsiniz.
