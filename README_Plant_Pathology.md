# Plant Pathology 2020 - Yaprak Hastalıkları Sınıflandırma

**Proje amacı**: Elma yaprağı görüntülerini 4 sınıfa (healthy, multiple_diseases, rust, scab) sınıflandırmak.

**Veri seti**: Plant Pathology 2020 (Kaggle) - yarışma verisi, `train.csv` + `images/`.
(Do not upload dataset to GitHub; use Kaggle Inputs.)

**Kullanılan yöntemler**:
- Veri ön işleme: Resize(224x224), normalization, train/val/test split
- Data augmentation: rotation, flip, zoom
- Model: CNN / Transfer Learning (ResNet/ EfficientNet opsiyonel)
- Eğitim: EarlyStopping, ReduceLROnPlateau

**Değerlendirme**:
- Accuracy & Loss grafikleri epoch bazında
- Confusion Matrix ve Classification Report
- Grad-CAM görselleştirmeleri

**Sonuçlar (özet)**:
- Validation Accuracy: %XX
- En çok karışan sınıflar: ...

**Kaggle Notebook**: (Kaggle notebook linkinizi buraya yapıştırın)
