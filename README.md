# 📊 Нийгмийн сүлжээний анализын төсөл

Энэхүү төсөл нь **нийгмийн сүлжээний өгөгдөлд анализ хийх**, **сүлжээ үүсгэх**, **төвity (centrality) хэмжигдэхүүнүүд тооцоолох**, **визуализаци хийх** зэрэг зорилготой. Python болон түгээмэл дата анализын сангуудыг ашиглан хийгдсэн.

---

## 📁 Төслийн бүтэц


---

## 🚀 Гол боломжууд

- Нийгмийн сүлжээний өгөгдөл цэвэрлэх, боловсруулалт хийх
- Сүлжээ (graph/network) үүсгэх, чиглэлтэй болон чиглэлгүй байдлаар
- Гол төвity хэмжигдэхүүнүүд:
  - Degree centrality
  - Betweenness centrality
  - Closeness centrality
  - Eigenvector centrality
- Сүлжээний визуализаци (matplotlib, networkx, plotly)
- Хувь хүний нөлөө, холбогдолыг үнэлэх

---

## 🧰 Ашигласан технологи

- Python ≥ 3.8
- `pandas`, `networkx`, `matplotlib`, `plotly`, `numpy`
- `jupyter`, `scikit-learn` (зэрэгцүүлэн ашиглаж болно)

---

## ⚙️ Суулгах заавар

1. Орчныг бэлтгэх:
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook
