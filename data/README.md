# Data

The dataset is **not** committed to this repository (12,000 images at 512 × 512 is too large for Git).

## Download

1. Go to https://data.mendeley.com/datasets/pjd7shvdgr
2. Click **Download All**
3. Upload the zip to your Google Drive, for example to `MyDrive/MD-SynReal12k/`

## Use in Google Colab

```python
from google.colab import drive
drive.mount('/content/drive')

!unzip -q "/content/drive/MyDrive/MD-SynReal12k/<file-name>.zip" -d /content/data
```

Replace `<file-name>` with the real name of the downloaded zip.

## Expected layout (to be confirmed after download)

```
data/
├── raw/          Original images as downloaded (Train / Validation / Test)
└── processed/    Images after format conversion and resizing to 224 × 224
```

Both folders are listed in `.gitignore`, so they stay on your own computer or Drive.
