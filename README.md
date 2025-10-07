# Pretrained-PhaseNet-Train
Tübitak 1001 projesi için geliştirilmiş kodun ilk halidir.
## Elde edilen değerlendirme metrikleri:
Accuracy -->	0.9475 -->	Modelin tüm test örnekleri içerisindeki genel doğruluk oranıdır. P ve S dalgalarının yaklaşık %94,75’ini doğru sınıfa yerleştirebilmiştir.

Precision (macro) -->	0.9477 -->	Modelin P veya S etiketi verdiği örneklerin %94,77’si doğru tahmin edilmiştir. Yanlış pozitif oranı oldukça düşüktür.

Recall (macro) -->	0.9435 -->	Gerçek P ve S örneklerinin %94,35’i doğru şekilde tespit edilmiştir. Modelin duyarlılığı yüksek düzeydedir.

F1 Skoru (macro) -->	0.9454 -->	Precision ve Recall değerlerinin harmonik ortalaması olup modelin genel dengeleme yeteneğini temsil eder. F1>0.94 seviyesi, faz ayrımı açısından literatürde güçlü bir performans olarak değerlendirilmektedir.

MAE -->	0.0525 -->	Ortalama mutlak hata 0.05 seviyesindedir. Bu, modelin her 20 dalgadan yalnızca birinde yanlış faz tahmini yaptığı anlamına gelir.

MSE -->	0.0525 -->	Kare hata değeri düşük olup büyük hataların (örneğin tamamen yanlış faz sınıflandırmaları) nadir gerçekleştiğini gösterir.

RMSE -->	0.2292 -->	Hataların karekök ortalaması da düşük olup, modelin tahminlerinin faz sınırlarına yakın olduğunu göstermektedir.
