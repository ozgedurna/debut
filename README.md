Kırmızı Şarap Kalitesi Sınıflandırması

Bu proje, kırmızı şarapların kalitesini belirlemek için bir sınıflandırma modeli geliştirmeyi amaçlamaktadır. Model, şarapların özelliklerini (örneğin, asit oranları) içeren bir veri seti üzerinde Gaussian Naive Bayes teoremini kullanarak sınıflandırma yapmaktadır.

Kullanılan Kütüphaneler 
scikit-learn
pandas
numpy
Veri Seti
Bu veri seti, kırmızı şarapların özelliklerini ve kalitelerini içermektedir. Veri seti, asit oranları, alkol dereceleri, pH değerleri gibi çeşitli kimyasal özellikleri içermektedir. Ayrıca, her bir şarabın kalitesi numaralandırılmıştır.

Model Performansı
Modelin performansını değerlendirmek için classification report kullanılmıştır. Modelin doğruluk (accuracy) ve f1-score değerleri incelenmiştir.

Model Değerlendirme:
Accuracy: Modelin doğru tahmin ettiği gözlem oranıdır.
F1-Score: Precision (kesinlik) ve recall (duyarlılık) metriklerinin harmonik ortalamasıdır.
