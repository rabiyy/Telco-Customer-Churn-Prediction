# Telco-Customer-Churn-Prediction

Telco müşteri kaybını (churn) tahmin etmek için geliştirilmiş uçtan uca makine öğrenmesi projesi. Logistic Regression'dan Optuna ile optimize edilmiş SVM'e kadar 7 farklı algoritmanın performans karşılaştırmasını içerir.

Bu proje, bir telekomünikasyon şirketindeki müşteri kaybını (churn) önceden tahmin etmek amacıyla makine öğrenmesi tekniklerini kullanır. Projenin temel hedefi, hangi müşterilerin aboneliğini iptal etme riski taşıdığını belirleyerek şirketin müşteri tutma stratejilerine veri odaklı destek sağlamaktır.

Öne Çıkan Özellikler:
Veri Analizi & Ön İşleme: Eksik verilerin temizlenmesi, TotalCharges dönüşümü ve özellik ölçeklendirme (Scaling).

Geniş Algoritma Yelpazesi: Logistic Regression, Decision Tree, Random Forest, KNN, AdaBoost, Naive Bayes ve SVM.

Gelişmiş Optimizasyon: SVM algoritması için klasik yöntemlerin ötesine geçilerek Optuna (Bayesian Optimization) ile hiperparametre ince ayarı yapılmıştır.

Performans Analizi: Modeller; Accuracy, Confusion Matrix ve özellikle sınıfları ayırma gücünü gösteren ROC-AUC skorları üzerinden karşılaştırılmıştır.

Özet Bulgular:
En yüksek başarıyı AdaBoost ve Random Forest modelleri sergilemiştir.

Naive Bayes, öznitelikler arasındaki bağımsızlık varsayımı nedeniyle bu veri setinde en düşük performansı göstermiştir.

Optuna kullanımı, SVM modelinin genelleme kapasitesini belirgin şekilde artırmıştır.
