# MAC Adresi

MAC (Media Access Control) adresi, ağ kartına üretici tarafından verilen ve her cihaza özgü olan fiziksel adrestir. Aynı yerel ağdaki cihazların birbirini tanımasını sağlar.

MAC adresi, **OSI modelinin Data Link katmanında (Katman 2)** çalışır ve yerel ağ (LAN) içerisinde iletişim için kullanılır.

## MAC Adresi Ne İşe Yarar?

* Ağdaki cihazları benzersiz şekilde tanımlar.
* Aynı yerel ağdaki cihazlar arasında veri iletimini sağlar.
* Switch'lerin veriyi doğru cihaza göndermesine yardımcı olur.
* Ağ erişim kontrolü (MAC Filtering) gibi güvenlik işlemlerinde kullanılabilir.

## MAC Adresinin Yapısı

Bir MAC adresi **48 bit (6 byte)** uzunluğundadır ve onaltılık (Hexadecimal) formatta gösterilir.

Örnek:

`00:1A:2B:3C:4D:5E`

veya

`00-1A-2B-3C-4D-5E`

İlk 3 byte üreticiyi (OUI), son 3 byte ise cihaza özel kimlik bilgisini temsil eder.

## MAC Adresi ile IP Adresi Arasındaki Fark

| MAC Adresi                 | IP Adresi                                  |
| -------------------------- | ------------------------------------------ |
| Fiziksel adrestir.         | Mantıksal adrestir.                        |
| Üretici tarafından atanır. | Ağ yöneticisi veya DHCP tarafından atanır. |
| Yerel ağda kullanılır.     | Ağlar arasında iletişim için kullanılır.   |
| Genellikle değişmez.       | Değişebilir (Dinamik IP).                  |

## Günlük Hayattan Örnek

Evdeki bilgisayarınız internete bağlanmak istediğinde, modem bilgisayarın **IP adresini** kullanarak hangi ağa ait olduğunu bilir. Aynı yerel ağ içerisinde ise veriyi doğru cihaza ulaştırmak için **MAC adresini** kullanır.

## Kısaca

**MAC Adresi, ağ kartına ait, her cihaza özel fiziksel adrestir ve yerel ağdaki cihazların birbirini tanımasını sağlar.**
