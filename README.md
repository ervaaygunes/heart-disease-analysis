# Kalp Hastalığı Tahmin Projesi

Bu proje, UCI Machine Learning Repository'den alınan "Heart Disease" (Kalp Hastalığı) veri setini kullanarak bir kalp hastalığı tahmin modeli geliştirmeyi amaçlamaktadır. Proje, veri ön işleme, Decision Tree (Karar Ağacı) modeli eğitimi, hiperparametre optimizasyonu ve model performansının değerlendirilmesi adımlarını içermektedir.

## Proje Yapısı

- **`Untitled.ipynb`**: Ana Jupyter Notebook dosyasıdır. Veri yükleme, ön işleme, model eğitimi, değerlendirme ve görselleştirme adımlarını içerir.
- **`data/`**: Bu klasör, proje için kullanılan tüm veri dosyalarını içerir. Ana veri seti `processed.cleveland.data` dosyasıdır.
- **`karar_agaci.png`**: Optimize edilmiş Decision Tree modelinin görselleştirmesini içerir.
- **`prd.md`**: Proje Gereksinimleri Dokümanı.
- **`.gitignore`**: Git tarafından takip edilmemesi gereken dosyaları ve klasörleri belirtir.

## Kurulum ve Çalıştırma

1.  **Depoyu Klonlama (Opsiyonel, eğer yerelde değilse):**
    ```bash
    git clone https://github.com/ervaaygunes/heart-disease-analysis.git
    cd heart-disease-analysis
    ```

2.  **Sanal Ortam Oluşturma ve Aktifleştirme:**
    Proje Python 3.x kullanılarak geliştirilmiştir. Bağımlılıkların yönetimi için bir sanal ortam kullanılması önerilir.
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # macOS/Linux için
    # venv\Scripts\activate    # Windows için
    ```

3.  **Gerekli Kütüphaneleri Yükleme:**
    Proje için gerekli olan temel kütüphaneler şunlardır: pandas, numpy, scikit-learn, matplotlib, seaborn, notebook, graphviz.
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn notebook graphviz
    ```
    `graphviz` kütüphanesinin sistem genelinde de kurulu olması gerekebilir (macOS için `brew install graphviz`).

4.  **Jupyter Notebook'u Başlatma:**
    ```bash
    jupyter notebook
    ```
    Tarayıcınızda Jupyter arayüzü açılacaktır. Buradan `Untitled.ipynb` dosyasını açarak projeyi çalıştırabilirsiniz.

## Veri Seti

Kullanılan ana veri seti "Cleveland" alt veri setidir ve `data/processed.cleveland.data` dosyasında bulunmaktadır. Diğer yardımcı dosyalar ve veri setinin farklı versiyonları da `data/` klasöründe mevcuttur. Veri seti hakkında daha fazla bilgi için [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease) sayfasını ziyaret edebilirsiniz.

## Katkıda Bulunma

Bu kişisel bir projedir, ancak öneri ve geri bildirimlere açıktır. 