# LatihanDataAnalist2024

# set up untuk wrailing on vs code
membuat folder baru (untuk wrailing)
```bash
mkdir proyek_analisis_data
```
pindah folder
```bash
cd proyek_analisis_data
```
Buat sebuah virtual environment 
```bash
pipenv install
```

Aktifkan virtual environment 
```bash
pipenv shell
```
Instal semua library yang dibutuhkan 
```bash
pip install numpy pandas scipy matplotlib seaborn jupyter
```

```bash
jupyter-notebook .
```
- Buat sebuah berkas baru bernama notebook.ipynb.

memanggil semua library
```bash
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

# set up streamlit
tambahkan kode berikut untuk menyimpan berkas data yang telah dibersihkan.
```bash
all_df.to_csv("all_data.csv", index=False)
```
Instal berbagai library yang digunakan
```bash
pip install streamlit babel
```
- bikin file dashboard.py
  
setup di page streamlitnya
```bash
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import streamlit as st
from babel.numbers import format_currency
sns.set(style='dark')
```

```bash

```
