# BikeSharingData
Dalam bike sharing kali ini, kita akan menganalisis dari dataset yang telah tersedia. Data yang terkandung ialah hour.csv dan day.csv

## Karakteristik Dataset
Dataset ini menjelaskan tentang penyewaan sepeda pada suatu kota. Penyewaan ini selain melibatkan pelanggan juga melibat pengguna umum sebagai market mereka. Dataset ini menampung data dari tahun 2011-2012 selama 731 hari. Data ini terbagi ke dalam data hari(day.csv) dan data jam(hour.csv)

## Analisis Dataset BikeSharing
**1. Tren yang terjadi dalam penyewaan sepeda**
Penyewaan sepeda dalam dataset ini memiliki tren yang fluktuatif. Hal ini ditandai dengan meningkatnya pengguna diawal tahun dan menurun di akhir tahun

**2. Perbandingan Registered User dan Casual User**
Perbandingan yang terjadi cukup signifikan dengan didominasi pelanggan dan hanya sedikit pengguna umumnya. 

# Install Dependencies

## Set Enviroment - Anaconda
```
conda create --name main-ds python=3.9
conda activate main-ds
pip install numpy pandas scipy matplotlib seaborn jupyter
pip install -r requirements.txt
```

## Set Enviroment - _Shell/Terminal_
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt

## Run Streamlit App
```
streamlit run dashboard.py
```
