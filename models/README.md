# Models

## Model1.ipynb
Statistical brightness feature regression baseline.

Includes:
- handcrafted nighttime-light features
- Linear Regression
- Random Forest Regression

---

## Model2.ipynb
CNN hybrid embedding regression model.

Pipeline:
County Image → CNN Feature Extractor → Embedding Extraction → Regression Model

Includes:
- CNN feature extraction
- Ridge Regression on CNN embeddings
- Random Forest Regression on CNN embeddings

---

## Model3.py
Improved hybrid CNN embedding regression pipeline.

Additional improvements:
- logarithmic brightness transformation (`log1p`)
- grayscale compositing
- illumination normalization
- proportional county scaling
- border-aware preprocessing
- tuned Random Forest regression
- improved embedding stability

Best-performing model:
- Random Forest regression on CNN embeddings
- Best R² ≈ 0.141
