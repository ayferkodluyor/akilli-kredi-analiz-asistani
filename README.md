🏦 Akıllı Kredi Analiz Asistanı

Bankacılık deneyimimi Python ve veri analizi becerilerimle bir araya getirdiğim bu projede, kredi değerlendirme sürecinde kullanılan bazı finansal göstergelerin birlikte incelenmesini ve dönemsel değişimlerin erken uyarı yaklaşımıyla görünür hale getirilmesini amaçladım.

🎯 Projenin Amacı

Akıllı Kredi Analiz Asistanı;
satış değişimi,
borç değişimi,
limit kullanım oranı,
ödeme gecikmeleri,
teminat durumu,
finansal verinin güncelliği
gibi göstergeleri belirlenen kurallar çerçevesinde değerlendirir.
Mevcut durum analizinin yanında son dört dönemdeki değişimleri de inceleyerek satış, borç, limit kullanımı ve ödeme davranışındaki olası bozulma eğilimlerini görünür hale getirir.

🔎 Analiz Yapısı

Uygulama iki temel değerlendirme gerçekleştirir:
1. Mevcut Durum Analizi
Belirlenen eşiklere göre finansal göstergeler kontrol edilir ve bir uyarı puanı oluşturulur.
Sonuç; Normal İzleme, İncelenmeli, Yüksek Dikkat seviyelerinden biriyle gösterilir.

2. Erken Uyarı / Trend Analizi
Son dört dönemde; satışların gelişimi, toplam borcun değişimi, limit kullanımındaki hareket, ödeme ve gecikme davranışı birlikte değerlendirilir.
Trend sonucu; Stabil İzlenmeli Erken Uyarı olarak gösterilir.
Uygulama ayrıca satış, borç ve limit kullanımındaki dönemsel değişimleri mini grafiklerle görselleştirir.

🛠 Kullanılan Teknolojiler
Python
Pandas
Tkinter

📊 Veri
Uygulamanın video demosunda kullanılan örnek veriler Python kodunun içerisinde yer almaktadır ve harici bir Excel dosyasına ihtiyaç duymaz.

🎥 Projenin Gelişim Aşamaları
Akıllı Kredi Analiz Asistanı tek aşamada değil, farklı geliştirme adımlarıyla oluşturuldu.

Bölüm 1
İlk çalışma ve kredi analiz yaklaşımının oluşturulması: https://www.youtube.com/watch?v=QojKFIheyqs

Bölüm 2
Uygulamanın geliştirilmesi ve analiz ekranının oluşturulması: https://www.youtube.com/watch?v=lSF2fQbXpV8

Bölüm 3 / Erken Uyarı Sistemi
Dönemsel trend analizi ve erken uyarı yaklaşımının eklendiği final sürüm: https://www.youtube.com/watch?v=OIhpCZ3uRcg

▶️ Çalıştırma

Gerekli paketi yükleyin: pip install -r requirements.txt
Ardından final Python dosyasını çalıştırın.

