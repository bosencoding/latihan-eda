# Latihan EDA — Exploratory Data Analysis with Python Cookbook

Latihan praktis berdasarkan buku **"Exploratory Data Analysis with Python Cookbook"** oleh Ayodele Oluleye.

**Dataset:** Kitsune Network Attack Dataset (Network Activity / Traffic Data)
- Sumber: https://www.kaggle.com/datasets/defchallenges/kitsune-network-attack-dataset
- Referensi notebook: https://www.kaggle.com/code/ernie55ernie/time-series-visualization-of-network-activity

## Struktur Latihan

| Chapter | Topik | Notebook | Status |
|---------|-------|----------|--------|
| 1 | Descriptive Statistics | `ch1/01_descriptive_stats_network.ipynb` | ✅ Tested |
| 2 | Data Manipulation | `ch2/02_data_manipulation_network.ipynb` | ✅ Tested |
| 3 | Data Visualization | `ch3/03_visualization_network.ipynb` | ✅ Tested |
| 8 | Text Data Analysis | `ch8/08_text_analysis_security.ipynb` | ✅ Tested |

## Cara Menjalankan

```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scipy plotly

# Jalankan Jupyter
jupyter notebook roles/backend/eda-latihan/
```

## Dataset

Setiap notebook sudah include code untuk generate **dummy dataset** yang menyerupai
struktur Kitsune Network Attack Dataset, jadi bisa langsung dijalankan tanpa download.

Untuk menggunakan dataset asli dari Kaggle:
```bash
# Install kaggle CLI
pip install kaggle

# Download dataset
kaggle datasets download defchallenges/kitsune-network-attack-dataset
unzip kitsune-network-attack-dataset.zip -d data/
```

## Soal Berbeda dari Buku

Soal-soal latihan ini dirancang berbeda dari contoh di buku, tetapi menggunakan
teknik EDA yang sama sesuai chapter masing-masing.
