# WAF (Web Application Firewall) Nedir?

WAF (Web Application Firewall), web uygulamalarını siber saldırılara karşı koruyan bir güvenlik sistemidir.

Normal bir firewall tüm ağ trafiğini korurken, **WAF yalnızca web uygulamalarına (HTTP/HTTPS trafiğine)** gelen istekleri analiz eder ve zararlı istekleri engeller.

## WAF Nasıl Çalışır?

1. Kullanıcı web uygulamasına istek gönderir.
2. İstek önce WAF'a ulaşır.
3. WAF isteği güvenlik kurallarına göre analiz eder.
4. Güvenli ise isteği web sunucusuna iletir.
5. Zararlı ise isteği engeller.

## WAF Ne İşe Yarar?

* Web uygulamalarını korur.
* Zararlı HTTP/HTTPS isteklerini engeller.
* Web trafiğini analiz eder.
* Güvenlik kurallarını uygular.
* Web uygulamalarının güvenliğini artırır.

## WAF'ın Koruduğu Yaygın Saldırılar

* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Dosya yükleme saldırıları
* Bot ve otomatik saldırılar

## WAF Nerelerde Kullanılır?

* E-ticaret siteleri
* Bankacılık uygulamaları
* Kurumsal web uygulamaları
* Kamu kurumlarının web siteleri
* Bulut tabanlı uygulamalar

## WAF ile Firewall Arasındaki Fark

| WAF                               | Firewall                               |
| --------------------------------- | -------------------------------------- |
| Web uygulamalarını korur.         | Ağ trafiğini korur.                    |
| HTTP/HTTPS trafiğini analiz eder. | Tüm ağ trafiğini denetler.             |
| Web saldırılarını engeller.       | Ağ seviyesindeki erişimi kontrol eder. |

## Günlük Hayattan Örnek

Bir alışveriş merkezine girerken önce güvenlik kontrolünden geçtiğinizi düşünün.

* **Firewall**, alışveriş merkezinin giriş kapısındaki güvenlik görevlisi gibidir; kimin içeri gireceğine karar verir.
* **WAF** ise mağazanın kapısındaki görevli gibidir; mağazaya gelen kişilerin şüpheli davranışlarını kontrol eder ve zararlı girişimleri engeller.

## Kısaca

**WAF, web uygulamalarını HTTP/HTTPS üzerinden gelen saldırılara karşı koruyan güvenlik sistemidir.**
