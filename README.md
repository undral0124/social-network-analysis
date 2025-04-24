# Нийгмийн Сүлжээний Шинжилгээ (Social Network Analysis)

Энэхүү төсөл нь `NetworkX`, `Matplotlib` зэрэг Python сангуудыг ашиглан нийгмийн сүлжээний шинжилгээ (SNA)-г хэрэгжүүлсэн жишээг харуулж байна.

## 📦 Орчны тохиргоо

1. Репозиторийг GitHub-оос татаж авна:

   ```bash
   git clone https://github.com/undral0124/social-network-analysis.git
   cd social-network-analysis
2. Хэрэгтэй Python сангуудыг суулгах:

   ```bash
   pip install -r requirements.txt

## Ашиглах заавар 

Шинжилгээний скриптийг ажиллуулах:

   ```bash
   python3 scripts/analyze_network.py

Өгөгдөл нэмэх ба удирдах

1. Өгөгдлийн файлуудыг байршуулах
CSV гэх мэт өгөгдлийг data/raw/ фолдерт нэмнэ:

```bash
edges.csv data/raw/

2. Өөрчлөлтүүдийг Git-д commit хийн push хийнэ:

```bash
git add data/raw/edges.csv
git commit -m "edges.csv өгөгдлийг нэмэв"
git push origin main

3. Гадаад эх сурвалжаас өгөгдөл татах (жишээ скрипт)

```bash
import pandas as pd

url = "https://raw.githubusercontent.com/your-dataset-source/edges.csv"
data = pd.read_csv(url)
data.to_csv("data/raw/edges.csv", index=False)

Ашигласан сангууд (requirements.txt)

```bash
networkx
matplotlib
pandas


