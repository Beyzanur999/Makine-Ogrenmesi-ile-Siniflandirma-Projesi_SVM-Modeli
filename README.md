# Makine Öğrenmesi ile Sınıflandırma Projesi - Support Vector Machines (SVM)

Bu proje, Global AI Hub bünyesindeki **Makine Öğrenmesi** eğitimi kapsamında gerçekleştirilmiş bir sınıflandırma problemidir. Gözetimli öğrenme algoritmalarından **Destek Vektör Makineleri (Support Vector Machines - SVM)** kullanılarak bir veri seti üzerinde eğitim, test ve hiperparametre optimizasyonu adımları uygulanmıştır.

---

## İçindekiler

- [Veri Seti](#veri-seti)
- [Kullanılan Yöntemler ve Adımlar](#kullanılan-yöntemler-ve-adımlar)
- [Model Değerlendirmesi](#model-değerlendirmesi)
- [Sonuçlar](#sonuçlar)
- [Kurulum ve Kullanım](#kurulum-ve-kullanım)
- [Kaggle Linki](#kaggle-linki)

---

## 📌 Proje Hakkında

Bu projede amaç, verilen veri seti üzerinde sınıflandırma yaparak **belirli bir hedef değişkeni** tahmin edebilecek bir makine öğrenmesi modeli oluşturmaktır. Bu kapsamda:

- Veri analiz ve görselleştirme işlemleri,
- Veri ön işleme adımları (eksik veri, ölçeklendirme vb.),
- SVM algoritması ile model eğitimi,
- GridSearchCV ile hiperparametre optimizasyonu,
- Model değerlendirme ve metrik hesaplamaları gerçekleştirilmiştir.

---

## Veri Seti

Projede kullanılan veri seti Kaggle üzerinden temin edilmiştir:

🔗 [Kaggle Dataset Linki](https://www.kaggle.com/datasets/beyzanurarslanta/heart-disease-uci)

Veri seti, iki sınıfa ayrılmış etiketlerden oluşmakta ve her örnek çeşitli sayısal özniteliklerle temsil edilmektedir. Bu nedenle ikili sınıflandırma (binary classification) problemine uygundur.

Veri seti üzerinde aşağıdaki işlemler yapılmıştır:

- Eksik verilerin kontrolü
- Standartlaştırma (StandardScaler)
- Eğitim/test veri setlerine ayrılma (%80 eğitim / %20 test)

---

## Kullanılan Yöntemler ve Adımlar

### 1. Veri Analizi ve Görselleştirme

- Değişkenlerin dağılımları incelendi
- Korelasyon matrisi çıkarıldı
- Hedef değişkenin dağılımı analiz edildi

### 2. Veri Ön İşleme

- `StandardScaler` ile özellikler normalize edildi
- Eğitim ve test veri seti ayrımı yapıldı
- Gerekli kütüphaneler ve SVC sınıfı import edildi

### 3. Model Eğitimi ve Optimizasyon

Model olarak `SVC (Support Vector Classifier)` kullanıldı.  
Hiperparametre ayarlamaları için `GridSearchCV` yöntemi uygulandı:

---
##LİNKLER

https://www.kaggle.com/datasets/beyzanurarslanta/heart-disease-uci
https://www.kaggle.com/code/beyzanurarslanta/makine-renmesi-ile-s-n-fland-rma-projesi



