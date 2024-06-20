# Büyük Veri Analitiği

Bu projede, Amazon kitap görüşleri veri seti üzerinde sözlük tabanlı duygu analizi gerçekleştirilmiş ve ardından çeşitli makine öğrenimi algoritmaları ile sınıflandırma işlemleri uygulanmıştır.

## Veri Seti

Veri seti, 1996 Mayıs - 2014 Temmuz tarihleri arasında Amazon'daki 3 milyon kullanıcının 212.404 kitap için yaptıkları 142.8 milyon görüşü içermektedir.
Kaggle üzerinden alınan [veri seti](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews?resource=download&select=Books_rating.csv) üzerinde uygulanmıştır.

## Değişkenler:

• Id (Kitap ID) \
• Title (Kitabın başlığı) \
• Price (Kitabın ücreti) \
• User_id (Kullanıcı ID) \
• ProfileName (Kullanıcının ismi) \
• review/helpfulness \
• review/score \
• review/time \
• review/summary (Görüş özeti) \
• review/text (Görüş) 

3 milyon gözlem ve 10 sütundan oluşan veri setinden sadece 
**review/text** sütunu ve **10.000** gözlemden oluşan örneklem çekilmiştir. Ve ilgili analizler elde edilen yeni veri seti üzerinden uygulanmıştır.
 
## KNIME Akış İçeriği 
- Veri setinin okutulması ve örneklem çekilmesi
- Verinin hazırlanması
- Veri Önişleme
- Pozitif, negatif ve nötr duygu atamaları
- H2O AI 5-katlı çapraz geçerlilik kullanılarak makine öğrenimi algoritmalarının uygulanması
- Her bir algoritmanın eğitim ve test kümelerinin doğruluk oranlarının elde edilmesi ve karşılaştırılması

## KNIME WORKFLOW
![Ekran Görüntüsü (266)](https://github.com/eceeknl/Big-Data-Analysis/assets/120251345/0e371f8d-8799-44cc-997e-622c980f16f7)
