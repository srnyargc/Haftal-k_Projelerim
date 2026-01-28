#Öğrenci Not Hesaplama Sistemi

Bu proje, bir sınıf listesindeki öğrencilerin sınav notlarını yönetmek, ortalamalarını hesaplamak ve başarı durumlarını analiz etmek için geliştirilmiş bir Python uygulamasıdır.

##Projenin Özellikleri
Veri Yapısı: Öğrenci isimleri bir tuple içinde, notlar ise her öğrenciye özel listeler barındıran bir dictionary (sözlük) yapısında tutulur.

Otomatik Hesaplama: sum() ve len() fonksiyonları kullanılarak her öğrencinin aritmetik ortalaması saniyeler içinde hesaplanır.

Mantıksal Denetim: Ortalaması 70 ve üzeri olan öğrenciler True (Geçti), altındakiler False (Kaldı) olarak işaretlenir.

İstatistiksel Analiz: * max() ve min() fonksiyonları ile sınıftaki en yüksek ve en düşük ortalamalar bulunur.

key=ortalama.get parametresi sayesinde, en yüksek/düşük notu alan öğrencilerin isimleri sözlükten otomatik olarak çekilir.

Görsel Çıktı: Sonuçlar f-string yapısı kullanılarak, notlar virgülden sonra tek basamağa yuvarlanmış (:.1f) şekilde ekrana yazdırılır.

##Kullanılan Teknikler
Python Sözlükleri (Dictionaries) ve Demetleri (Tuples)

Dinamik Veri Çekme (max & min with key parameter)

Mantıksal Operatörler (if / else ve karşılaştırmalar)

String Formatlama (f-strings)

##Nasıl Kullanılır?
Bilgisayarınızda Anaconda veya VS Code yüklü olduğundan emin olun.

OrtHesapÖdevi.ipynb dosyasını çalıştırın.

Sınıf listesini veya notları değiştirmek isterseniz notlar sözlüğündeki değerleri güncellemeniz yeterlidir.