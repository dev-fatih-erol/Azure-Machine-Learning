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
