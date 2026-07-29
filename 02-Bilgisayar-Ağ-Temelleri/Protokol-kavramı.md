# Protokol kavramı

Protokol, ağ üzerindeki cihazların birbiriyle nasıl iletişim kuracağını belirleyen kurallar bütünüdür. Cihazların veri alışverişi yapabilmesi için aynı protokolleri kullanması gerekir.

Her protokol farklı bir amaç için geliştirilmiştir. Aşağıda siber güvenlikte en sık karşılaşılan protokoller yer almaktadır.

---

## TCP (Transmission Control Protocol)

TCP, güvenilir veri iletimi sağlayan bir iletişim protokolüdür.

Özellikleri:

* Verilerin eksiksiz iletilmesini sağlar.
* Hata kontrolü yapar.
* Paketlerin doğru sırayla ulaşmasını sağlar.
* Bağlantı odaklıdır (Connection-Oriented).

Kullanım Alanları:

* HTTP
* HTTPS
* FTP
* SSH
* SMTP

Kısaca:

**TCP, güvenilir ve bağlantı odaklı veri iletim protokolüdür.**

---

## UDP (User Datagram Protocol)

UDP, hızlı veri iletimi sağlayan ancak teslim garantisi vermeyen bir protokoldür.

Özellikleri:

* Bağlantısızdır (Connectionless).
* Hızlıdır.
* Hata kontrolü yapmaz.
* Paketlerin sırası garanti edilmez.

Kullanım Alanları:

* DNS
* Online oyunlar
* Canlı yayınlar
* VoIP

Kısaca:

**UDP, hızlı ancak teslim garantisi olmayan iletişim protokolüdür.**

---

## HTTP (HyperText Transfer Protocol)

Web tarayıcısı ile web sunucusu arasındaki iletişimi sağlayan protokoldür.

Varsayılan Port:

* **80/TCP**

Özellikleri:

* Veriler şifrelenmeden iletilir.
* Günümüzde güvenli olmadığı için HTTPS tercih edilir.

Kısaca:

**HTTP, web sayfalarının iletilmesini sağlayan protokoldür.**

---

## HTTPS (HyperText Transfer Protocol Secure)

HTTP'nin SSL/TLS ile şifrelenmiş güvenli sürümüdür.

Varsayılan Port:

* **443/TCP**

Özellikleri:

* Verileri şifreler.
* Kimlik doğrulaması sağlar.
* Veri bütünlüğünü korur.

Kısaca:

**HTTPS, güvenli web iletişim protokolüdür.**

---

## DNS (Domain Name System)

Alan adlarını IP adreslerine çeviren sistemdir.

Örnek:

`www.google.com` → `142.250.x.x`

Varsayılan Port:

* **53/UDP**
* **53/TCP**

Kısaca:

**DNS, alan adlarını IP adreslerine çeviren sistemdir.**

---

## DHCP (Dynamic Host Configuration Protocol)

Ağa bağlanan cihazlara otomatik IP adresi dağıtır.

Varsayılan Port:

* **67/UDP (Sunucu)**
* **68/UDP (İstemci)**

Kısaca:

**DHCP, cihazlara otomatik IP adresi atayan protokoldür.**

---

## FTP (File Transfer Protocol)

Dosya transferi için kullanılan protokoldür.

Varsayılan Port:

* **20/TCP**
* **21/TCP**

Özellikleri:

* Veriler şifrelenmez.
* Güvenli alternatif olarak SFTP veya FTPS tercih edilir.

Kısaca:

**FTP, dosya aktarımı için kullanılan protokoldür.**

---

## SSH (Secure Shell)

Uzak sistemlere güvenli bağlantı kurmayı sağlayan protokoldür.

Varsayılan Port:

* **22/TCP**

Kullanım Alanları:

* Sunucu yönetimi
* Güvenli terminal bağlantısı

Kısaca:

**SSH, güvenli uzaktan erişim protokolüdür.**

---

## SMTP (Simple Mail Transfer Protocol)

E-posta gönderiminde kullanılan protokoldür.

Varsayılan Port:

* **25/TCP**
* **587/TCP**
* **465/TCP (SSL/TLS)**

Kısaca:

**SMTP, e-posta göndermeyi sağlayan protokoldür.**

---

## POP3 (Post Office Protocol v3)

E-postaları sunucudan indirerek istemciye aktaran protokoldür.

Varsayılan Port:

* **110/TCP**
* **995/TCP (SSL/TLS)**

Kısaca:

**POP3, e-postaları indirerek erişim sağlayan protokoldür.**

---

## IMAP (Internet Message Access Protocol)

E-postaların sunucu üzerinde kalmasını sağlayan protokoldür.

Varsayılan Port:

* **143/TCP**
* **993/TCP (SSL/TLS)**

Özellikleri:

* Birden fazla cihazdan senkronize kullanım sağlar.

Kısaca:

**IMAP, e-postaları sunucu üzerinde senkronize şekilde yöneten protokoldür.**

---

## LDAP (Lightweight Directory Access Protocol)

Dizin hizmetlerine erişmek ve kullanıcı bilgilerini yönetmek için kullanılan protokoldür.

Varsayılan Port:

* **389/TCP**
* **636/TCP (LDAPS)**

Kullanım Alanları:

* Active Directory
* Kullanıcı kimlik doğrulama
* Merkezi kullanıcı yönetimi

Kısaca:

**LDAP, dizin hizmetlerini yönetmek ve sorgulamak için kullanılan protokoldür.**

---

## SMB (Server Message Block)

Ağ üzerinden dosya ve yazıcı paylaşımını sağlayan protokoldür.

Varsayılan Port:

* **445/TCP**

Kullanım Alanları:

* Windows dosya paylaşımı
* Ortak klasör erişimi

Kısaca:

**SMB, ağ üzerinden dosya ve yazıcı paylaşımını sağlayan protokoldür.**

---

## RDP (Remote Desktop Protocol)

Windows sistemlerine uzaktan masaüstü bağlantısı kurmayı sağlayan protokoldür.

Varsayılan Port:

* **3389/TCP**

Kullanım Alanları:

* Uzak bilgisayar yönetimi
* Sistem yönetimi

Kısaca:

**RDP, windows bilgisayarlara uzaktan masaüstü bağlantısı sağlayan protokoldür.**
