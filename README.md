# Kişilik Tipi Tahmini: Dışa Dönük mü İçe Dönük mü?

Bu proje, bireylerin davranışsal verilerine dayanarak **içe dönük (Introvert)** veya **dışa dönük (Extrovert)** kişilik tiplerini tahmin etmeyi amaçlamaktadır. Python ve makine öğrenmesi yöntemleri kullanılarak veri analizi ve sınıflandırma modeli geliştirilmiştir.

## 📊 Veri Seti

Projedeki veri seti Kaggle üzerinden alınmıştır:

🔗 [Extrovert vs Introvert - Personality Behavior Dataset](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data)

Veri setinde aşağıdaki gibi özellikler bulunmaktadır:

- Sosyal davranışlar
- Duygusal tepkiler
- İkili sorular (örneğin: sahne korkusu, sosyalleşme sonrası yorgunluk)
- Kişilik tipi (Extrovert / Introvert)

## 🧠 Proje Amacı

Amaç, verilen davranışsal verilere göre bireyin **içe dönük** mü yoksa **dışa dönük** mü olduğunu sınıflandıran bir model geliştirmektir.

## 🛠️ Kullanılan Teknolojiler

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (görselleştirme)
- Jupyter Notebook (Kaggle Kernel)

## 📈 Çalışma Adımları

1. Veri Yükleme
2. Keşifsel Veri Analizi (EDA)
3. Veri Ön İşleme
   - Eksik değer kontrolü
   - Kategorik verilerin sayısallaştırılması
4. Model Eğitimi
   - Train/Test ayırma
   - Sınıflandırma modeli kurulumu (Örn: Lojistik Regresyon, Random Forest)
5. Model Değerlendirme
   - Doğruluk (Accuracy), Karışıklık Matrisi, Precision/Recall/F1-score

## 📌 Sonuç

Model, yaklaşık **%92 doğruluk** oranına ulaşmıştır ve hem içe dönük hem de dışa dönük sınıflar için dengeli sonuçlar vermiştir.

## 📁 Dosya İçeriği

- `personality_type_prediction.ipynb`: Veri analizi, ön işleme ve modelleme adımlarını içeren Jupyter defteri.

## 🚀 Nasıl Çalıştırılır?

Bu notebook’u aşağıdaki platformlarda çalıştırabilirsiniz:

- [Kaggle](https://www.kaggle.com/code) (Kod kısmında)
- Jupyter Notebook (lokal bilgisayarda)

