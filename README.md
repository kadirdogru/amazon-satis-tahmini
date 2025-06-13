# Amazon Satış Verileri ile Sipariş Başarısı Tahmini

Bu projede, Amazon satış verileri kullanılarak bir siparişin başarıyla tamamlanıp tamamlanmayacağını tahmin etmek amacıyla sınıflandırma modelleri geliştirilmiştir.

## 📌 Proje Amacı

Siparişlerin iptal edilip edilmeyeceğini önceden tahmin ederek:
- Lojistik süreçleri optimize etmek
- Müşteri memnuniyetini artırmak
- Operasyonel riski azaltmak

## 📊 Kullanılan Veri Seti

- Kaynak: [Kaggle - Unlock Profits with E-Commerce Sales Data](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data)
- Gözlem sayısı: 128,975
- Özellik sayısı: 24

## 🔍 Uygulanan Adımlar

1. Eksik veri temizliği ve doldurma (median / mode)
2. Kategorik verilerin one-hot encoding ile dönüştürülmesi
3. Gereksiz sütunların çıkarılması
4. Eğitim/test ayrımı (%80 - %20)

## 🤖 Kullanılan Modeller

- Random Forest Classifier
- Logistic Regression (karşılaştırmalı)

## 📈 Model Performansı

| Model               | Accuracy | F1 Score |
|---------------------|----------|----------|
| Random Forest       | 0.9988   | 0.9993   |
| Logistic Regression | 0.9987   | 0.9993   |

## 📁 Proje Dosyaları

- `Amazon Sale Report.csv` : Ham veri seti
- `deneme.ipynb` : Modelleme süreci
- `KadirDogru_132230024.docx` : Proje raporu
- `grafikler/` : Çıktı görselleri (confusion matrix, feature importance, vb.)

## 🧠 Sonuç ve Öneriler

Model, riskli siparişleri yüksek doğrulukla tespit edebilmektedir. Bu sayede iptal olasılığı yüksek siparişler için erken aksiyon alınarak müşteri deneyimi ve operasyonel verimlilik artırılabilir.

## 🛠️ Kullanılan Kütüphaneler

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## 👤 Geliştirici

**Kadir Doğru**  
Bursa Uludağ Üniversitesi  
Yönetim Bilişim Sistemleri  
