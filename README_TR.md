# Siber Tehdit Tespiti ve Guvenlik Analizi

Bu proje, SOC (Security Operations Center) mantigina uygun olarak hazirlanmis bir siber guvenlik veri seti uzerinde kesifsel veri analizi (EDA), ag trafigi analizi ve MITRE ATT&CK mapping calismalarini icermektedir.

## Proje Amaci

Bu projenin temel amaci:

- Siber saldiri davranislarini analiz etmek
- Ag trafigi ozelliklerini incelemek
- Farkli saldiri turlerini yorumlamak
- MITRE ATT&CK framework'u ile saldiri davranislarini eslestirmek
- SOC bakis acisiyla tehdit analizi yapmak

## Kullanilan Teknolojiler

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- MITRE ATT&CK Navigator

## Yapilan Analizler

### Exploratory Data Analysis (EDA)

- Attack type distribution analizi
- Protocol distribution analizi
- Top destination ports analizi
- Bytes sent analizi
- Korelasyon analizi

### MITRE ATT&CK Mapping

Projede tespit edilen saldiri davranislari MITRE ATT&CK framework'u ile eslestirilmistir.

Kullanilan tekniklerden bazilari:

- T1110 - Brute Force
- T1046 - Network Service Scanning
- T1498 - Network Denial of Service
- T1190 - Exploit Public-Facing Application
- T1071 - Application Layer Protocol
- T1059 - Command and Scripting Interpreter

## Proje Yapisi

```text
Cyber-Threat-Detection/
│
├── data/
├── notebooks/
├── visuals/
├── README.md
├── README_TR.md
├── README_EN.md
└── requirements.txt
```

## Gelecek Gelistirmeler

- Gercek zamanli dashboard sistemi
- Threat monitoring paneli
- Gelismis anomaly detection
- Makine ogrenmesi tabanli saldiri tespiti
- SIEM benzeri analiz yapisi

## Not

Bu proje egitim ve portfolyo amacli hazirlanmistir.
