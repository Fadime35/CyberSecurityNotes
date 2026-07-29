# Subnet Hesaplama

Subnet hesaplama, bir IP adresinin kaç alt ağa bölüneceğini ve her alt ağda kaç cihaz bulunabileceğini belirleme işlemidir.

## Temel Formüller

* **Alt ağ (Subnet) sayısı =** `2ⁿ`
* **Her alt ağdaki kullanılabilir host sayısı =** `2ʰ - 2`

Burada:

* **n:** Alt ağ (Subnet) için ayrılan bit sayısı
* **h:** Host (Cihaz) için kalan bit sayısı

> `-2` yapılmasının sebebi, bir adresin ağ adresi (Network Address), bir adresin ise yayın adresi (Broadcast Address) olarak ayrılmasıdır.

---

## Örnek 1

IP Adresi:

`192.168.1.0/24`

Bu ağda:

* Network biti = 24
* Host biti = 8

Host sayısı:

`2⁸ - 2 = 254`

Yani bu ağda **254 cihaz** kullanılabilir.

---

## Örnek 2

`192.168.1.0/26`

Bu kez:

* Network biti = 26
* Host biti = 6

Host sayısı:

`2⁶ - 2 = 62`

Yani her alt ağda **62 cihaz** bulunabilir.

Subnet sayısı:

`26 - 24 = 2 bit`

`2² = 4`

Yani **4 adet subnet** oluşur.

---

## /24 Ağının /26'ya Bölünmesi

| Subnet | Ağ Adresi     | Kullanılabilir IP Aralığı     | Broadcast     |
| ------ | ------------- | ----------------------------- | ------------- |
| 1      | 192.168.1.0   | 192.168.1.1 - 192.168.1.62    | 192.168.1.63  |
| 2      | 192.168.1.64  | 192.168.1.65 - 192.168.1.126  | 192.168.1.127 |
| 3      | 192.168.1.128 | 192.168.1.129 - 192.168.1.190 | 192.168.1.191 |
| 4      | 192.168.1.192 | 192.168.1.193 - 192.168.1.254 | 192.168.1.255 |

---

## CIDR Tablosu

| CIDR | Subnet Maskesi  | Kullanılabilir Host |
| ---- | --------------- | ------------------: |
| /24  | 255.255.255.0   |                 254 |
| /25  | 255.255.255.128 |                 126 |
| /26  | 255.255.255.192 |                  62 |
| /27  | 255.255.255.224 |                  30 |
| /28  | 255.255.255.240 |                  14 |
| /29  | 255.255.255.248 |                   6 |
| /30  | 255.255.255.252 |                   2 |

## Kısaca

Subnet hesaplamada temel mantık:

1. **CIDR değerinden host bitini bul.**
2. **Host sayısını `2ʰ - 2` formülüyle hesapla.**
3. **Alt ağ sayısını `2ⁿ` formülüyle bul.**
4. **Host sayısı kadar artarak ağ adreslerini oluştur.**

Bu mantığı öğrendiğinizde subnet sorularının büyük çoğunluğunu rahatlıkla çözebilirsiniz.
