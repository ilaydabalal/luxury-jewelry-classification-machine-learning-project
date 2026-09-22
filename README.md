
---

# 💎 Luxury Jewelry Classification & Machine Learning Project


---


A data mining and machine learning project that processes a dataset of **4,204 jewelry images** (necklaces, earrings, rings, bracelets, watches) collected from online platforms of luxury brands using the Orange data mining tool, and classifies them using various algorithms.

**About the Project**

In this project, images were converted into numerical vectors using the *image embedding* method. Models were trained using **Neural Network**, **Logistic Regression**, and **kNN (k-Nearest Neighbors)** algorithms. Tested with *10-Fold Cross-Validation*, the model performances were compared, and the highest accuracy (**93.3%**) was achieved using the Neural Network model.

**Installation and Running**

1. Ensure that **Orange Data Mining** is installed on your computer.
2. Open the `şıkır şıkır.ows` workflow file included in the project folder using Orange.
3. Explore the workflow steps, data processing pipelines, and examine the evaluation results (*Confusion Matrix* and performance metrics).

**Folder Structure**

```text
takı_siniflandirma_projesi/
├── şikır şıkır.ows                # Orange platform model and workflow file
└── README.md                      # Project documentation

```

**How It Works**

* 4,204 images compiled from luxury jewelry brand sources are categorized into 5 main classes (necklace, earring, ring, bracelet, watch).
* Image features are extracted using Orange to make them suitable for machine learning algorithms.
* 3 different classification algorithms (Neural Network, Logistic Regression, kNN) are trained and evaluated on the same dataset.
* Performances are compared using Accuracy, Precision, Recall, and F1-Score metrics.


Orange veri madenciliği platformunu kullanarak lüks markaların (Cartier, Swarovski, Bulgari vb.) online mecralarından otomatik veya sistemli olarak topladığım **4.204 adet görselden** oluşan takı veri setini (kolye, küpe, yüzük, bileklik, saat) işlediğim ve makine öğrenmesi modelleriyle sınıflandırdığım projedir.

**Proje Hakkında**

Bu projede, görseller öznitelik çıkarımı (*image embedding*) yöntemiyle sayısal vektörlere dönüştürülmüş; **Neural Network (Yapay Sinir Ağı)**, **Logistic Regression (Lojistik Regresyon)** ve **kNN (k-Nearest Neighbors)** algoritmalarıyla modeller eğitilmiştir. 10 katmanlı çapraz doğrulama (*10-Fold Cross-Validation*) ile test edilen modellerin performansları kıyaslanmış ve **%93.3 doğruluk oranı** sunan Neural Network modeli ile en başarılı sonuç elde edilmiştir.


**Kurulum ve Çalıştırma**

1. Bilgisayarınızda **Orange Data Mining** uygulamasının yüklü olduğundan emin olun.
2. Proje klasöründe yer alan `şıkır şıkır.ows` dosyasını Orange programı ile açın.
3. Akış üzerindeki veri yükleme ve modelleme adımlarını inceleyebilir, algoritmaların test sonuçlarını (*Confusion Matrix* ve performans metriklerini) gözlemleyebilirsiniz.

**Klasör Yapısı**

```text
takı_siniflandirma_projesi/
├── şikır şıkır.ows                # Orange platformu modelleme ve iş akışı dosyası
└── README.md                      # Proje dokümantasyonu

```

🛠️ **Nasıl Çalışır?**

* Lüks takı markalarının sitelerinden derlenen 4.204 görsel 5 ana sınıfa (kolye, küpe, yüzük, bileklik, saat) ayrılmıştır.
* Orange ortamında görsel öznitelikler çıkarılarak makine öğrenmesine uygun hale getirilmiştir.
* 3 farklı sınıflandırma algoritması (Neural Network, Logistic Regression, kNN) aynı veri seti üzerinde koşturulmuştur.
* Doğruluk (Accuracy), Kesinlik (Precision), Duyarlılık (Recall) ve F1-Skoru metrikleriyle performansları karşılaştırılmıştır.

---
