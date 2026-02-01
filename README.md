# 📊 Superstore SQL & Python Sales Analysis

Bu proje, bir perakende zincirinin satış verilerini analiz etmek amacıyla oluşturulmuştur. Ham veri seti Pandas kütüphanesi ile işlenmiş ve sorgulanabilir bir **SQLite** veritabanına dönüştürülmüştür.

## 🛠 Kullanılan Teknolojiler
- **Dil:** Python 3.14.2
- **Kütüphaneler:** Pandas, SQLite3, Matplotlib
- **Ortam:** Jupyter Notebook (VS Code)

## 🔍 Yapılan Analizler
1. **Kârlılık Analizi:** Hangi ürün kategorilerinin daha yüksek kâr marjına sahip olduğu SQL `GROUP BY` ve `SUM` fonksiyonları ile hesaplandı.
2. **İndirim Stratejisi:** İndirim oranlarının net kâr üzerindeki negatif etkileri `HAVING` filtrelemesi ile tespit edildi.
3. **Müşteri Sadakati:** En çok alışveriş yapan "Champion" müşteri segmenti belirlendi.
4. **Zaman Serisi:** Satışların yıllar içindeki trendi `Matplotlib` ile görselleştirildi.

## 🚀 Nasıl Çalıştırılır?
1. Repoyu klonlayın.
2. VS Code üzerinde `analiz.ipynb` dosyasını açın.
3. Gerekli kütüphaneleri yükleyin: `pip install pandas matplotlib`
