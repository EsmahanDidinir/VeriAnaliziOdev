# VeriAnaliziOdev
Red Wine Quality Prediction - Veri Analizi ve Görselleştirme
Bu proje, kırmızı şarapların kimyasal özellikleri ve kalite ile ilgili analizleri içermektedir. Veri setinde, şarapların pH değeri, asidite, şeker oranı gibi kimyasal bileşenlerle birlikte kaliteye dair bilgiler yer almaktadır. Bu README, veri setinin hazırlanmasından, sürekli değişkenlerin analizine kadar yapılan adımları özetlemektedir.

1. Veri Setinin Hazırlanması
İlk adımda, veri seti bir CSV dosyasından yüklenmiştir. Bu veri seti, şarapların kimyasal özelliklerini ve kalitelerini içeren sütunlardan oluşmaktadır.

Veri setine ilk bakış yapılarak, ilk 5 ve son 5 gözlem görüntülenmiştir. Bu, veri setinin yapısını anlamamıza yardımcı olmuştur. Ayrıca, veri setindeki tüm sütun isimleri ve veri türleri kontrol edilmiştir.

Veri setindeki sayısal ve kategorik sütunlar ayrılarak, her bir veri türü için ayrı listeleme yapılmıştır. Bu işlem, veri ön işleme adımlarında farklı veri türlerine uygun işlemler yapabilmek için önemlidir.

2. Eksik Veriler ve Görselleştirme
Eksik veriler, veri setinde kontrol edilmiştir. Eksik değerler, görselleştirme araçları kullanılarak analiz edilmiştir. Bu adımda, eksik verilerin hangi sütunlarda bulunduğu ve ne kadar eksik veri olduğu görsel olarak sunulmuştur.

Ayrıca, veri setine rastgele eksik değerler eklenmiştir. Bu işlem, eksik verilerle başa çıkma yöntemlerini öğrenmek amacıyla yapılmıştır.

3. Veri Filtreleme
Veri setindeki pH değeri 3.5 ve üzeri olan şaraplar filtrelenmiştir. Bu filtreleme ile pH değeri 3.5 ve daha yüksek olan şaraplara ait veriler seçilmiştir. Bu sayede, belirli bir pH değeri aralığına odaklanarak daha detaylı analizler yapılması sağlanmıştır.

4. Görselleştirme
Filtrelenmiş verilerin görselleştirilmesi amacıyla birkaç analiz yapılmıştır:

pH Değerlerinin Dağılımı: Seaborn kütüphanesi ile pH değeri 3.5 ve üzeri olan şarapların kategorik dağılımı görselleştirilmiştir. Bu görselleştirme, pH değeri olan şarapların sıklığının nasıl dağıldığını anlamamıza yardımcı olur.

Yoğunluk (KDE) Grafiği: pH değeri için bir yoğunluk grafiği oluşturulmuştur. Bu grafik, pH değerinin hangi aralıklarda daha yoğun olduğunu ve hangi pH değerlerinin daha yaygın olduğunu gösterir. KDE analizi, dağılımın daha ayrıntılı bir şekilde anlaşılmasını sağlar.

5. Sürekli Değişkenlerin Analizi
Veri setindeki sayısal değişkenler (pH, asidite, vb.) seçilerek analiz edilmiştir. Bu sayısal değişkenlerin özet istatistikleri hesaplanmıştır. Bu istatistikler, her sütunun temel özelliklerini (ortalama, standart sapma, minimum, maksimum değerler vb.) içerir.

Bu adımda, veri setinin sayısal sütunlarıyla ilgili temel bilgileri elde etmek için özet istatistikler hesaplanmıştır.

Sonuçlar:
Veri Hazırlama: Veri setindeki sayısal ve kategorik özellikler ayrılmış, eksik veriler görselleştirilmiş ve rastgele eksik değerler eklenmiştir.
Veri Filtreleme ve Görselleştirme: pH değeri 3.5 ve üzeri olan şaraplar filtrelenmiş ve bu şarapların sıklığı görselleştirilmiştir.
KDE Grafiği: pH değerinin yoğunluğu üzerine yapılan analiz, pH değeri aralıklarındaki yoğunluğu gösteren bir grafikle sunulmuştur.
Sürekli Değişken Analizi: Sayısal değişkenlerin özet istatistikleri hesaplanmış ve görselleştirilmiştir.
Kullanılan Kütüphaneler:
Pandas: Veri işleme ve analiz için kullanılmıştır.
Matplotlib ve Seaborn: Veri görselleştirme işlemleri için kullanılmıştır.
NumPy: Sayısal hesaplamalar için kullanılmıştır.
Missingno: Eksik verilerin görselleştirilmesi için kullanılmıştır.
