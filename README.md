🎯 Projenin Amacı

Bu proje, bir müşteri churn (terk etme) tahmin modeli geliştirmek amacıyla hazırlanmış bir Datathon çalışmasıdır. Amaç, müşterilerin bankadan ayrılma olasılığını belirlemek, riskli müşteri segmentlerini tanımlamak ve bu bilgiler doğrultusunda aksiyon alınmasını sağlamaktır.

Bu çalışma, verilen veri seti üzerinden öngörüsel modelleme, veri analizi, özellik mühendisliği ve model değerlendirme adımlarını içeren uçtan uca bir makine öğrenimi sürecini sergilemek üzere hazırlanmıştır.

🧹 Veri Ön İşleme Süreci

Yüksek kaliteli bir churn modeli elde etmek için kapsamlı veri ön işleme adımları uygulanmıştır:

Eksik değer analizi ve temizliği

Aykırı değer yakalama ve iyileştirme

Davranışsal ve istatistiksel özellik mühendisliği

Kategorik değişkenlerin etkili biçimde kodlanması

Sayısal özelliklerin ölçeklendirilmesi

Bu süreç, modelin genel başarısını artıran en kritik aşamalardan biridir.

🤖 Modelleme Yaklaşımı

Bu projede ileri seviye boosting algoritmaları kullanılarak güçlü bir churn tahmin modeli geliştirilmiştir. Kullanılan ana modeller:

LightGBM (LGBM)

XGBoost (XGB)

CatBoost

Bu üç model, yalnızca tekil olarak değil, aynı zamanda ensemble (topluluk) bir yapı içinde kullanılarak daha kararlı, genellenebilir ve yüksek doğruluk sağlayan sonuçlar elde edilmiştir.

Modelleme sürecinin temel aşamaları:

Eğitim/Test veri ayrımı

Hiperparametre optimizasyonu

K-Fold çapraz doğrulama

Ensemble stratejisinin oluşturulması

Performans metriklerinin değerlendirilmesi

Bu yapı sayesinde model, hem hız hem de doğruluk açısından güçlü bir dengede çalışacak şekilde optimize edilmiştir.


📊 Sonuçlar ve Performans Değerlendirmesi

Ensemble yöntemiyle birleştirilen LGBM + XGBoost + CatBoost modelleri, tekil modellere göre belirgin bir performans artışı sağlamıştır. Özellikle boosting algoritmalarının karmaşık müşteri davranışlarını yakalama kabiliyeti churn tahmini için büyük avantaj oluşturmuştur.

Değerlendirilen temel metrik: ROC-AUC

Sonuçlar, modelin başarılı bir şekilde churn davranışını tahmin ettiğini ve Datathon ortamında rekabetçi bir performans sunduğunu göstermektedir.

✨ Teşekkürler

Bu çözümü incelemek için teşekkür ederim. Her türlü yorum, öneri veya iş birliği talebiniz için memnuniyetle yardımcı olurum.
