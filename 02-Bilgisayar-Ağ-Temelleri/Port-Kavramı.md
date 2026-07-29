# Port Kavramı

Port, bir cihaz üzerinde çalışan uygulama veya servislerin ağ üzerinden iletişim kurmasını sağlayan mantıksal iletişim noktasıdır.

Bir IP adresi cihazı tanımlarken, **port numarası** o cihaz üzerinde hangi uygulama veya servise veri gönderileceğini belirler.

Örneğin, aynı bilgisayarda hem bir web sunucusu hem de bir e-posta sunucusu çalışabilir. Gelen verinin hangi uygulamaya iletileceği port numarası sayesinde anlaşılır.

## Port Numaraları

Port numaraları **0 ile 65535** arasında değişir ve üç gruba ayrılır:

* **0 - 1023:** Well-Known (İyi Bilinen) Portlar
* **1024 - 49151:** Registered (Kayıtlı) Portlar
* **49152 - 65535:** Dynamic / Private (Dinamik) Portlar

## Yaygın Portlar

|  Port | Protokol | Kullanım Amacı                 |
| ----: | -------- | ------------------------------ |
| 20/21 | FTP      | Dosya transferi                |
|    22 | SSH      | Güvenli uzaktan bağlantı       |
|    23 | Telnet   | Güvensiz uzaktan bağlantı      |
|    25 | SMTP     | E-posta gönderimi              |
|    53 | DNS      | Alan adı çözümleme             |
| 67/68 | DHCP     | IP adresi dağıtımı             |
|    80 | HTTP     | Web trafiği                    |
|   110 | POP3     | E-posta alma                   |
|   143 | IMAP     | E-posta alma ve senkronizasyon |
|   443 | HTTPS    | Güvenli web trafiği            |
|   445 | SMB      | Dosya ve yazıcı paylaşımı      |
|  3389 | RDP      | Uzak Masaüstü bağlantısı       |

## Siber Güvenlik Açısından Önemi

Açık portlar saldırganlar tarafından hedef alınabilir. Bu nedenle:

* Gereksiz portlar kapatılmalıdır.
* Güvenlik duvarı (Firewall) ile erişim kontrol edilmelidir.
* Açık portlar düzenli olarak taranmalıdır.

## Günlük Hayattan Örnek

Bir apartmanı düşünün:

* **IP adresi** apartmanın adresidir.
* **Port numarası** ise daire numarasıdır.

Kargo doğru apartmana (IP) geldikten sonra doğru daireye (Port) teslim edilir.

## Kısaca

**Port, bir cihaz üzerindeki uygulama veya servislerin ağ üzerinden iletişim kurmasını sağlayan mantıksal iletişim noktasıdır.**
