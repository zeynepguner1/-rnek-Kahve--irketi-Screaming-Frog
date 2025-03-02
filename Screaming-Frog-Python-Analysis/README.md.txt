Starbucks Web Sitesi Teknik Sağlık Analizi

Bu proje, Örnek bir kahve şirketinin web sitesinin teknik sağlık durumunu değerlendirmek için hazırlanmıştır.  
Veriler Screaming Frog ile toplanmış, Python kullanılarak analiz edilmiştir.

---

Proje İçeriği

Bozuk linkler, meta açıklama ve başlık hataları gibi önemli teknik sorunlar tespit edildi.  
Hataların site sağlığına olan etkisi puanlanarak 100 üzerinden bir skor hesaplandı.  

---

Kullanılan Araçlar ve Teknolojiler

-Screaming Frog – Web tarama ve veri toplama  
-Python (Pandas, Matplotlib, Seaborn) – Veri analizi ve görselleştirme  


Sonuçlar ve Bulgular  

Genel Sağlık Skoru: `61.9 / 100`  

 📉 Hata Dağılımı  
Bozuk Linkler: 3 hata  
Kısa ve Yinelenen Meta Başlıkları: 15'er hata  
Eksik H2 Etiketleri: 12 hata  

İyileştirme Önerileri  

Hızlı Düzeltmeler: 
- Bozuk linkleri kaldır veya güncelle  
- Kısa meta başlıklarını 50-60 karakter aralığına çek  
- Yinelenen meta açıklamalarını özgünleştir  

Orta Vadeli Çözümler: 
- Eksik H1 ve H2 etiketlerini ekleyerek başlık yapısını iyileştir  
- Yönlendirme hatalarını gider  