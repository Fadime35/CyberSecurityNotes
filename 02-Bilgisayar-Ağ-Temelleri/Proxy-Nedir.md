# Proxy Nedir?

Proxy, istemci (kullanıcı) ile hedef sunucu arasında aracı görevi gören bir sistemdir. Kullanıcının yaptığı istekler önce proxy sunucusuna gider, ardından hedef sunucuya iletilir. Sunucudan gelen cevap da yine proxy üzerinden kullanıcıya ulaşır.

Proxy'nin temel amacı; güvenliği artırmak, trafiği kontrol etmek ve kullanıcı ile hedef sunucu arasında aracılık yapmaktır.

## Proxy Nasıl Çalışır?

1. Kullanıcı bir web sitesine erişmek ister.
2. İstek önce proxy sunucusuna gönderilir.
3. Proxy isteği kontrol eder.
4. Uygunsa isteği hedef sunucuya iletir.
5. Sunucudan gelen cevap kullanıcıya geri gönderilir.

## Proxy Ne İşe Yarar?

* Kullanıcı ile sunucu arasında aracılık yapar.
* İnternet trafiğini denetler.
* Belirli web sitelerine erişimi engelleyebilir.
* IP adresini gizleyebilir.
* Sık kullanılan içerikleri önbelleğe (Cache) alarak erişimi hızlandırabilir.

## Proxy Türleri

### Forward Proxy

Kullanıcı adına internete erişim sağlar.

Kullanım Alanları:

* Kurumsal ağlar
* İnternet erişim kontrolü
* İçerik filtreleme

---

### Reverse Proxy

Sunucuların önünde bulunur ve istemcilerden gelen istekleri ilgili sunucuya yönlendirir.

Kullanım Alanları:

* Yük dengeleme (Load Balancing)
* Güvenlik
* Performans artırma
* Web sunucularını gizleme

## Proxy ile Firewall Arasındaki Fark

| Proxy                                          | Firewall                                         |
| ---------------------------------------------- | ------------------------------------------------ |
| İstemci ile sunucu arasında aracıdır.          | Ağ trafiğini güvenlik kurallarına göre denetler. |
| Trafiği yönlendirebilir ve önbelleğe alabilir. | Trafiğe izin verir veya engeller.                |
| IP adresini gizleyebilir.                      | Yetkisiz erişimleri engeller.                    |

## Günlük Hayattan Örnek

Bir sekreteri düşünün.

Ziyaretçiler doğrudan müdürle görüşmek yerine önce sekretere gelir. Sekreter isteği değerlendirir ve uygun görürse müdüre iletir.

Proxy de benzer şekilde çalışır; kullanıcı ile hedef sunucu arasında aracılık yaparak istekleri kontrol eder ve iletir.

## Kısaca

**Proxy, kullanıcı ile hedef sunucu arasında aracılık yapan, internet trafiğini yöneten ve güvenliği artıran bir sistemdir.**
