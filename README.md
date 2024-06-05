Kalp Krizi Riski Tahmini
Bu proje, çeşitli makine öğrenimi algoritmalarını kullanarak kalp krizi riskini tahmin etmeyi amaçlamaktadır. Veri seti, yaş, cinsiyet, kan basıncı, kolesterol seviyeleri, EKG sonuçları ve egzersiz bilgileri gibi sağlık ölçümlerini içermektedir. Hedef değişken, kalp hastalığı olup olmadığını belirten bir sınıflandırma problemidir.

Kullanılan Modeller
Projede aşağıdaki makine öğrenimi modelleri kullanılmıştır:

Decision Tree (CART)
Support Vector Classifier (SVC)
K-Nearest Neighbors (KNN)
Gradient Boosting Machines (GBM)
Random Forests
XGBoost
LightGBM
CatBoost
Yapay Sinir Ağları (Neural Networks)
Değerlendirme Metrikleri
Her modelin performansı, aşağıdaki metrikler kullanılarak değerlendirilmiştir:

Mean Squared Error (MSE)
F1 Skoru
Doğruluk Skoru (Accuracy)
Veri Seti Açıklaması
Veri seti, çeşitli sağlık ölçümlerini ve kalp hastalığı durumunu içermektedir. Aşağıda her bir değişkenin açıklaması yer almaktadır:

age: Yaş
sex: Cinsiyet (1 = Erkek, 0 = Kadın)
cp: Göğüs ağrısı tipi (0-3 arası kodlanmış değerler)
trestbps: Dinlenme halindeki kan basıncı (mm Hg)
chol: Serum kolesterolü (mg/dl)
fbs: Açlık kan şekeri > 120 mg/dl (1 = doğru, 0 = yanlış)
restecg: Dinlenme elektrokardiyografisi sonuçları (0, 1, 2)
thalach: Ulaşılan maksimum kalp hızı
exang: Egzersizin neden olduğu anjina (1 = doğru, 0 = yanlış)
oldpeak: Dinlenmeye göre egzersizin neden olduğu ST depresyonu
slope: Egzersizin zirvesinin eğimi ST segmenti (0-2 arası kodlanmış değerler)
ca: Florosopi ile renklendirilen majör damarların sayısı (0-3)
thal: Talasemi durumu (0 = normal, 1 = sabit kusur, 2 = geri döndürülebilir kusur)
target: Hedef değişken (0 = daha az kalp krizi olasılığı, 1 = daha fazla kalp krizi olasılığı)
Veri seti öğrenme amacıyla alınmıştır. Verilerin kaynağı: UCI Heart Disease Dataset

Proje Dosyaları
heart_disease_data.csv: Kullanılan veri seti.
model_evaluation.py: Modellerin eğitildiği ve değerlendirildiği Python betiği.
README.md: Proje hakkında genel bilgileri içeren dosya.

Gerekli Kütüphaneler
Bu projede kullanılan başlıca kütüphaneler şunlardır:

pandas
numpy
scikit-learn
xgboost
lightgbm
catboost
Sonuçlar
Her modelin performansına ilişkin sonuçlar, ortalama kare hatası (MSE), F1 skoru ve doğruluk skorları bazında karşılaştırılmıştır. Sonuçlar, hangi algoritmaların kalp krizi riskini tahmin etmede daha etkili olduğunu göstermektedir.

Katkıda Bulunma
Katkıda bulunmak isterseniz, lütfen bir fork oluşturun, kendi dalınızda değişiklik yapın ve bir pull request gönderin.

