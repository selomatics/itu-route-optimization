# İTÜ Kampüsü Yaya Rota Optimizasyonu 🚶‍♂️📍

Bu proje, İstanbul Teknik Üniversitesi (İTÜ) kampüsü içinde en kısa yaya rotasını hesaplamak için OpenStreetMap (OSM) ve NetworkX kütüphanelerini kullanmaktadır.

## 📌 Özellikler
- OSM verisinden kampüs içindeki yolları çeker.
- Başlangıç ve hedef noktaları belirleyerek en kısa rotayı hesaplar.
- Dijkstra algoritması ile mesafe optimizasyonu yapar.
- Harita üzerinde rotayı görselleştirir.
- Sonuçları GeoJSON formatında kaydeder.

## 🛠 Kullanılan Teknolojiler
- Python
- OSMnx & NetworkX
- Matplotlib
- GeoJSON

## 🚀 Kullanım
Projeyi klonladıktan sonra aşağıdaki komutları çalıştırabilirsiniz:

```bash
git clone https://github.com/kullaniciadiniz/itu-route-optimization.git
cd itu-route-optimization
pip install -r requirements.txt
python route_optimization.py
```

## 📊 Çıktılar
- Harita üzerinde en kısa yaya rotası
- Hesaplanan rota uzunluğu (metre cinsinden)
- GeoJSON formatında rota verisi



