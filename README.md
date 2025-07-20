5. hafta 2. odevde de  yanlislikla bitirme projesi baglanti linki koydugum icin buraya yonlendiriyor  5. hafta icin dogru link https://github.com/ayyucea/Patika-Veri-Analizi-Hafta5-.git

# Patika-Veri-Analizi-2.-Bitirme-Projesi

Dosya boyutu büyük olduğu için Drive bağlantısını paylaşıyorum 

https://drive.google.com/file/d/1Y72B4NRTbIIEBqqo7XJ9wDLPDpqusqIo/view?usp=sharing

https://app.powerbi.com/links/f7CVyxEXzE?ctid=4b55b462-e98f-4bba-a0b1-9d792ff93016&pbi_source=linkShare


# 📊 Power BI Satış ve Müşteri Analizi Projesi

Bu proje, Power BI kullanılarak oluşturulmuş bir **satış ve müşteri analizi** raporudur. Veriler `.csv` dosyaları üzerinden alınmış, ardından DAX komutlarıyla ölçüler hesaplanmış ve farklı perspektiflerden analizler oluşturulmuştur.

## 🔍 Proje Hakkında

Amaç, satış verilerini farklı boyutlardan analiz ederek:

- Şirketin genel performansını özetlemek
- Müşteri segmentasyonunu ortaya koymak
- Kategorilere göre satışları incelemek
- Zaman bazlı (saat, gün) satış eğilimlerini belirlemek


## 🧠 Hesaplanan Ölçüler (DAX Komutları)

Power BI'da aşağıdaki önemli ölçüler hesaplanmıştır:

- `Toplam Satış Adeti = SUM(siparisdetay[AMOUNT])`
- `Toplam Ciro = SUM(siparisdetay[LINETOTAL])`
- `Toplam Sipariş Sayısı = COUNTROWS(siparis)`
- `Toplam Müşteri Sayısı = DISTINCTCOUNT(siparis[USERID])`
- `Müşteri Başına Ciro = DIVIDE([Toplam Ciro], [Toplam Müşteri Sayısı])`
- `Müşteri Başına Adet = DIVIDE([Toplam Satış Adeti], [Toplam Müşteri Sayısı])`
- `Ortalama Sipariş Tutarı = AVERAGE(siparisdetay[LINETOTAL])`
- `Erkek Müşteri Sayısı`, `Kadın Müşteri Sayısı`, `Tekil Müşteri Sayısı`
- `Saatlik Satış Tutarı`, `Hafta Tipine Göre Satış`

## 📊 Rapor Panelleri

Rapor 3 farklı bakış açısından oluşturulmuştur:

### 1. 🧾 Satış ve Sipariş Özeti Paneli
- Toplam satış adetleri, cirolar, sipariş ve müşteri sayıları
- Haftaiçi vs haftasonu satış karşılaştırması
- Saatlik satış analizleri

### 2. 👥 Müşteri Perspektifi
- Erkek/Kadın müşteri dağılımı
- Bölgelere göre müşteri sayısı
- İstanbul'daki en çok harcayan 10 müşteri

### 3. 📦 Kategori Perspektifi
- Yaş gruplarına göre harcama analizi
- Orta yaş grubunun ürün kategorilerine göre harcama dağılımı


## 📌 Kullanılan Teknolojiler

- Power BI Desktop
- DAX (Data Analysis Expressions)
- CSV veri işleme



