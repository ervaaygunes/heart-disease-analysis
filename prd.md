# Project Requirements Document (PRD)

## Proje Adı
Heart Disease Veri Seti Üzerinde Decision Tree Tabanlı Sınıflandırma ve Performans Değerlendirmesi

## Amaç
Bu projenin amacı, UCI Machine Learning Repository'de yer alan "Heart Disease" veri setini kullanarak Decision Tree tabanlı sınıflandırma algoritmalarıyla kalp hastalığı riskini tahmin etmek, çeşitli değerlendirme metrikleriyle model performansını ölçmek ve sonuçları daha önce yapılmış akademik bir çalışmanın sonuçlarıyla karşılaştırarak sunmaktır.

## Veri Seti
- **Kaynak:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)
- **Açıklama:** Veri seti, bireylerin demografik, klinik ve laboratuvar verilerini içerir. Amacı, kişilerin kalp hastalığına sahip olup olmadığını tahmin etmektir.
- **Hedef Değişken:** Heart Disease Presence (binary classification: 0 = no disease, 1 = disease)

## Kullanılacak Yöntemler

### Sınıflandırma Algoritması
- Decision Tree (CART)


### Performans Ölçütleri
- Accuracy (Doğruluk)
- Precision (Kesinlik)
- Recall (Duyarlılık / Sensitivity)
- Specificity (Özgüllük)
- F1-Score
- ROC Curve ve AUC değeri
- Confusion Matrix

## Araçlar ve Teknolojiler
- Python 3.x
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn (veri görselleştirme)
- Jupyter Notebook 

## Adımlar

1. **Veri Hazırlığı**
   - Veri setinin yüklenmesi ve temizlenmesi
   - Eksik verilerin işlenmesi
   - Özellik seçimi ve dönüştürme
   - Eğitim/test veri bölünmesi

2. **Modelleme**
   - Decision Tree modeli oluşturulması
   - Model eğitimi ve test edilmesi

3. **Performans Değerlendirmesi**
   - Accuracy, sensitivity, specificity, F1-score hesaplanması
   - ROC eğrisi çizimi ve AUC hesaplaması
   - Confusion Matrix görselleştirmesi

4. **Akademik Karşılaştırma**
   - Literatürden bir çalışma bulunması (Heart Disease verisi ile Decision Tree kullanılan)
   - Çalışmanın bulgularının kısa özetlenmesi
   - Kendi model sonuçlarınız ile tablo ve grafiklerle karşılaştırma

5. **Sunum**
   - Elde edilen bulguların grafiklerle desteklenerek raporlanması
   - Yorumların eklenmesi: Modelin güçlü ve zayıf yönleri
   - Akademik çalışma ile karşılaştırmanın detaylı açıklaması

## Beklenen Çıktılar
- Jupyter Notebook/Colab dosyası (kod ve açıklamalarla)
- Karar ağacı görselleştirmeleri
- Performans metriklerinin tablo ve grafik sunumu
- Literatür karşılaştırma tablosu
- Sunum dosyası (PDF veya PowerPoint)
                     |

## Başarı Kriterleri
- Modelin en az %80 doğruluk oranına ulaşması
- ROC AUC değerinin %85 üzeri olması
- Görselleştirme ile desteklenmiş, anlaşılır sonuçlar
- En az bir akademik kaynak ile uygun karşılaştırma

## Ek Notlar
- Modelin yorumlanabilirliği (özellikle Decision Tree) önemlidir.
- Şeffaflık ve tekrar üretilebilirlik için kodlar ayrıntılı açıklanmalıdır.
- Akademik çalışma doğru kaynak belirtilerek alıntılanmalıdır.

