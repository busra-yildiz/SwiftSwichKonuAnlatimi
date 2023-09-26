# SwiftSwichKonuAnlatimi
Swift programlama dilinde switch ifadesi, bir değeri veya ifadeyi birden çok koşula göre karşılaştırmak ve 
farklı işlemler yapmak için kullanılır. switch ifadesi, belirli bir değerin farklı durumlara göre nasıl işleneceğini 
belirlemek için kullanışlıdır. İşte Swift'te switch ifadesini kullanmanın temel yapısı:
switch deger {
case durum1:
    // Durum 1 için kod
case durum2:
    // Durum 2 için kod
case durum3:
    // Durum 3 için kod
default:
    // Hiçbir durum uymuyorsa yapılacak kod
}
Bu yapının temel bileşenleri şunlardır:

switch: Değerleri karşılaştırmak için anahtar kelime.
deger: Karşılaştırmak istediğiniz değer veya ifade.
case: Bir durumu temsil eder ve eğer deger belirtilen durum ile eşleşirse ilgili kod çalıştırılır.
default: Hiçbir case ifadesi eşleşmezse veya hiçbir koşul sağlanmazsa çalıştırılacak kod bloğudur.
İşte bir örnek:
let meyve = "elma"

switch meyve {
case "elma":
    print("Bu bir elmadır.")
case "armut":
    print("Bu bir armuttur.")
case "muz":
    print("Bu bir muzdur.")
default:
    print("Bu bir bilinmeyen meyvedir.")
}
Bu örnekte, meyve değişkeni switch ifadesi içindeki case ifadeleriyle karşılaştırılır ve eşleşen
bir case bulunursa ilgili kod çalıştırılır. Eğer hiçbir case ifadesi eşleşmezse default bloğu çalışır.

switch ifadesi aynı zamanda sayılar, karakterler, enum (sıralı türler), ve diğer veri türleri için de 
kullanılabilir. Ayrıca, birden fazla case ifadesini aynı işlemi yapacak şekilde birleştirmenize olanak tanır.

Swift'te switch ifadesi, koşullu kodunuzu daha temiz ve okunabilir hale getirmenizi sağlar ve 
birden çok durumu ele almak için oldukça kullanışlıdır.
