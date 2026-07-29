# Subnet Mantığı

Subnet (Alt Ağ), büyük bir ağı daha küçük ve yönetilebilir parçalara ayırma işlemidir. Bu işleme **Subnetting** denir.

Subnetting sayesinde ağ trafiği daha düzenli yönetilir, performans artırılır ve güvenlik iyileştirilir.

## Subnet Neden Kullanılır?

* Büyük ağları daha küçük parçalara ayırmak
* Ağ performansını artırmak
* Ağ trafiğini azaltmak
* Güvenliği artırmak
* IP adreslerini daha verimli kullanmak

## Subnet Nasıl Çalışır?

Bir IP adresi iki bölümden oluşur:

* **Network (Ağ) kısmı:** Cihazın hangi ağa ait olduğunu gösterir.
* **Host (Cihaz) kısmı:** Ağ içindeki cihazı tanımlar.

Subnet maskesi, IP adresinin hangi kısmının **Network**, hangi kısmının **Host** olduğunu belirler.

Örnek:

* IP Adresi: `192.168.1.25`
* Subnet Maskesi: `255.255.255.0`

Bu örnekte:

* **192.168.1** → Ağ (Network)
* **25** → Cihaz (Host)

Yani `192.168.1.x` adresine sahip cihazlar aynı alt ağda bulunur ve doğrudan birbirleriyle iletişim kurabilir.

## Subnet Kullanımına Örnek

Bir şirkette 300 bilgisayar olduğunu düşünelim.

Hepsini tek bir ağda toplamak yerine;

* Muhasebe
* İnsan Kaynakları
* Yazılım
* Siber Güvenlik

departmanları için ayrı subnetler oluşturulabilir.

Böylece ağ daha düzenli yönetilir ve gereksiz ağ trafiği azaltılır.

Kısaca:

**Subnet, büyük bir ağı daha küçük alt ağlara bölerek yönetimi, performansı ve güvenliği artırma yöntemidir.**
