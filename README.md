# uzay_similatoru
Uzay Simülasyonu (Space Simulation Project):
Bu proje, bir bilim insanının Güneş sistemindeki farklı gezegenlerde (Merkür'den Neptün'e kadar) temel fizik kanunlarını simüle etmesini sağlayan C dili ile geliştirilmiş konsol tabanlı bir uygulamadır.

Proje Hakkında:
Bu uygulama, Bursa Teknik Üniversitesi Bilgisayar Mühendisliği Algoritmalar ve Programlama dersi dönemi projesi kapsamında geliştirilmiştir. Projenin temel amacı, karmaşık fiziksel hesaplamaları C dilinin ileri seviye özelliklerini (pointer aritmetiği, dinamik bellek yönetimi mantığı vb.) kullanarak gerçekleştirmektir.

Teknik Özellikler:
Proje geliştirilirken aşağıdaki teknik kısıtlamalara ve kurallara tam uyum sağlanmıştır:

Pointer Aritmetiği: Dizi elemanlarına erişim sırasında [] operatörü yerine tamamen *(ptr + i) yapısı kullanılmıştır.

Modüler Yapı: Her fizik deneyi (9 farklı deney) bağımsız fonksiyonlar olarak tanımlanmıştır.

Hata Yönetimi: Geçersiz veri girişlerini (harf girilmesi vb.) engellemek için Buffer Cleaning (Tampon Temizleme) mekanizması kurulmuştur.

Ternary Operatörü: Mutlak değer hesaplamaları ve yön seçimleri için if-else yerine ? : operatörü tercih edilmiştir.

Simüle Edilen Deneyler:
Serbest Düşme (Distance of Free Fall)

Yukarı Atış (Maximum Height)

Ağırlık Hesaplama (Weight on Planets)

Kütleçekimsel Potansiyel Enerji

Hidrostatik Basınç

Arşimet Kaldırma Kuvveti

Basit Sarkaç Periyodu

Sabit İp Gerilmesi

Asansör Deneyi (Etkin Ağırlık Değişimi)

Kurulum ve Çalıştırma
Projeyi yerel makinenizde çalıştırmak için:

Depoyu klonlayın:

Bash

git clone https://github.com/kullanici-adiniz/proje-isminiz.git
C derleyicisi (gcc) ile derleyin:

Bash

gcc main.c -o uzay_simulasyonu -lm
Çalıştırın:

Bash

./uzay_simulasyonu

örnek çıktı:

Bilim insaninin adini giriniz: Gemini
--- DENEY MENUSU ---
1. Serbest Dusme
...
Secim: 1
Sure (s): 5
Dunya: 122.62 m
Jupiter: 309.88 m
...
 Lisans
Bu proje eğitim amaçlı geliştirilmiştir.
