# Azure Machine Learning

Azure Machine Learning, bulut tabanlı bir hizmettir ve kullanıcılara makine öğrenimi modellerini oluşturma, eğitme ve dağıtma imkanı sağlar.

## Components

1. Sample Data (Örnek Veri): Azure Machine Learning'de kullanılabilir örnek veri setlerini temsil eder. Bu veri setleri, model eğitimi veya testi için kullanılabilir ve Azure Machine Learning atölyeleri veya örnek uygulamalar için örnek veriler sağlar.
   * Flight Delay Data
   * IMDB Movie Titles
   * Movie Ratings
   * Weather Dataset

2. Data Transformation (Veri Dönüşümü): Verileri işlemek, dönüştürmek ve hazırlamak için kullanılan bileşenleri içerir. Bu bileşenler, veri ön işleme adımlarını gerçekleştirir ve veri setlerini öznitelik çıkarma, ölçeklendirme, eksik veri doldurma gibi işlemlerle dönüştürebilir.
   * Add Columns: Bir veri kümesine yeni bir sütun eklemek için kullanılan bir 
     işlevdir. Bu işlev, mevcut veri kümesine belirli bir mantıksal veya 
     hesaplamalı işlemi uygulayarak yeni bir sütun oluşturmanıza olanak 
     sağlar. Örneğin, bir sütunu ikiye bölmek, sütundaki değerleri bir diziye 
     dönüştürmek veya bir sütunu filtrelemek gibi işlemleri gerçekleştirmek 
     için AddColumns kullanılabilir.

   * Add Rows: Mevcut bir veri kümesine yeni satırlar eklemek için kullanılan 
     bir işlemdir. Bu işlem, varolan bir veri kümesine, başka bir veri 
     kaynağından veya hesaplamalı bir işlemden gelen yeni satırları eklemek 
     için kullanılabilir. Örneğin, bir veri kümesine güncel verileri düzenli 
     olarak eklemek veya birden fazla veri kaynağını birleştirerek genişletmek 
     için "Add Rows" işlemi kullanılabilir.

3. Computer Vision (Bilgisayarlı Görü): Bu bileşen, Azure Machine Learning'de görüntü işleme ve analizi yapmak için kullanılır. Görüntü sınıflandırma, nesne tespiti, yüz tanıma, görüntü segmentasyonu gibi görevleri gerçekleştirmek için önceden eğitilmiş veya özelleştirilebilir modeller sağlar.

4. Model Scoring & Evaluation (Model Skorlama ve Değerlendirme): Bu bileşenler, eğitilmiş bir makine öğrenimi modelini kullanarak tahmin yapmak, sınıflandırma sonuçları elde etmek veya modelin performansını değerlendirmek için kullanılır. Metrik hesaplamaları, karar sınırları, doğruluk matrisleri gibi işlemleri içerir.

5. Machine Learning Algorithms (Makine Öğrenimi Algoritmaları): Bu başlık altında, Azure Machine Learning'de kullanılabilen çeşitli makine öğrenimi algoritmaları yer alır. Bu algoritmalar, sınıflandırma, regresyon, kümeleme, boyut indirgeme ve diğer çeşitli görevler için kullanılabilir.

6. Text Analytics (Metin Analitiği): Metin verilerini analiz etmek için kullanılan bileşenleri içerir. Metin sınıflandırma, duygu analizi, metin özetleme gibi görevleri gerçekleştirmek için önceden eğitilmiş modeller veya özel metin analiz teknikleri sağlar.

7. Python Language (Python Dili): Azure Machine Learning'de Python programlama diliyle çalışmayı sağlayan bileşenlerdir. Python tabanlı işlevler, Python kitaplıklarının kullanımı, özel Python betikleri gibi özellikleri içerir.

8. Data Input and Output (Veri Girişi ve Çıkışı): Verilerin Azure Machine Learning ortamına nasıl alınacağı ve çıkarılacağı ile ilgili bileşenleri içerir. Veri kaynaklarına bağlanma, veri setlerini okuma/yazma, veri formatlarını dönüştürme gibi işlemleri kolaylaştırır.

9. Recommendation (Öneri Sistemleri): Bu bileşenler, kullanıcı tercihlerini ve davranışlarını temel alarak öneri sistemleri oluşturmayı sağlar. Ürün önerileri, içerik önerileri, kişiselleştirilmiş öneriler gibi uygulamalar için kullanılır.

10. R Language (R Dili): Azure Machine Learning'de R programlama diliyle çalışmayı sağlayan bileşenlerdir. R tabanlı işlevler, R paketlerinin kullanımı, özel R betikleri gibi özellikleri içerir.

11. Feature Selection (Öznitelik Seçimi): Bu bileşenler, makine öğrenimi modellerinde kullanılacak en önemli özniteliklerin seçilmesini sağlar. Modelin performansını artırmak ve gereksiz öznitelikleri elerken anlamlı bilgiyi korumak için kullanılır.

12. Anomaly Detection (Anomali Tespiti): Bu bileşenler, veri setlerindeki anormallikleri veya anomalileri tespit etmek için kullanılır. Anomalileri belirlemek ve ayırt etmek için istatistiksel veya örüntü tabanlı yöntemler kullanılır.

13. Statistical Functions (İstatistiksel İşlevler): Bu başlık altında, temel istatistiksel hesaplamaları gerçekleştirmek için kullanılan bileşenler yer alır. Ortalama, standart sapma, korelasyon gibi istatistiksel hesaplamaları içerir.

14. Model Training (Model Eğitimi): Bu bileşenler, makine öğrenimi modellerini eğitmek için kullanılır. Algoritmaları yapılandırmak, model parametrelerini ayarlamak, hiperparametre optimizasyonu gibi işlemleri içerir.

15. Web Service (Web Hizmeti): Bu bileşenler, eğitilmiş bir makine öğrenimi modelini web hizmeti olarak dağıtmak için kullanılır. Dışarıdan erişilebilen API'ler sağlar ve modelin çevrimiçi olarak kullanılmasını sağlar.
