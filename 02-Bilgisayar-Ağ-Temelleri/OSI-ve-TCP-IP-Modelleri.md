# OSI ve TCP/IP Modelleri

OSI ve TCP/IP modelleri, ağ üzerindeki cihazların nasıl iletişim kurduğunu açıklayan katmanlı yapılardır. Bu modeller sayesinde verilerin ağda nasıl iletildiği standart hale getirilmiştir.

---

# OSI Modeli

OSI (Open Systems Interconnection), ağ iletişimini **7 katmanda** açıklayan referans modelidir.

## OSI'nin 7 Katmanı

### 7. Application (Uygulama)

Kullanıcının doğrudan etkileşimde bulunduğu katmandır.

Örnek Protokoller:

* HTTP
* HTTPS
* FTP
* SMTP
* DNS

Görevi:

* Uygulamalara ağ hizmeti sunar.

---

### 6. Presentation (Sunum)

Verilerin doğru formatta iletilmesini sağlar.

Görevleri:

* Şifreleme
* Sıkıştırma
* Veri biçimlendirme

---

### 5. Session (Oturum)

İki cihaz arasındaki oturumu başlatır, yönetir ve sonlandırır.

Görevleri:

* Oturum oluşturma
* Oturum yönetimi
* Oturum sonlandırma

---

### 4. Transport (Taşıma)

Verilerin güvenilir şekilde iletilmesini sağlar.

Protokoller:

* TCP
* UDP

Görevleri:

* Hata kontrolü
* Veri sıralama
* Segmentlere ayırma

---

### 3. Network (Ağ)

Verilerin farklı ağlar arasında yönlendirilmesini sağlar.

Protokoller:

* IP
* ICMP

Cihaz:

* Router

Görevi:

* En uygun yolu belirleyerek paketleri hedefe ulaştırmak.

---

### 2. Data Link (Veri Bağı)

Aynı ağdaki cihazlar arasında iletişim sağlar.

Özellikleri:

* MAC adresi kullanır.
* Frame oluşturur.

Cihaz:

* Switch

---

### 1. Physical (Fiziksel)

Verilerin elektriksel veya optik sinyaller halinde iletilmesini sağlar.

Örnekler:

* Ethernet kablosu
* Fiber kablo
* Wi-Fi

Cihaz:

* Hub
* Kablo

---

# TCP/IP Modeli

TCP/IP modeli günümüzde internet üzerinde kullanılan ağ modelidir ve **4 katmandan** oluşur.

## Katmanları

### 4. Application

OSI'nin Application, Presentation ve Session katmanlarını kapsar.

Protokoller:

* HTTP
* HTTPS
* DNS
* FTP
* SMTP
* SSH

---

### 3. Transport

Verilerin güvenilir şekilde iletilmesini sağlar.

Protokoller:

* TCP
* UDP

---

### 2. Internet

IP adresleme ve yönlendirme işlemlerini gerçekleştirir.

Protokoller:

* IP
* ICMP
* ARP

---

### 1. Network Access

Fiziksel ağ iletişimini gerçekleştirir.

Örnekler:

* Ethernet
* Wi-Fi

---

# OSI ve TCP/IP Karşılaştırması

| OSI Modeli   | TCP/IP Modeli  |
| ------------ | -------------- |
| Application  | Application    |
| Presentation | Application    |
| Session      | Application    |
| Transport    | Transport      |
| Network      | Internet       |
| Data Link    | Network Access |
| Physical     | Network Access |

---

# Katmanların Görevleri

| Katman       | Temel Görevi                                  |
| ------------ | --------------------------------------------- |
| Application  | Kullanıcıya ağ hizmeti sunar.                 |
| Presentation | Veriyi şifreler ve biçimlendirir.             |
| Session      | Oturumları yönetir.                           |
| Transport    | Güvenilir veri iletimi sağlar.                |
| Network      | Paketleri yönlendirir.                        |
| Data Link    | Aynı ağdaki cihazlar arasında iletişim kurar. |
| Physical     | Veriyi fiziksel ortamda iletir.               |

---

# Paketlerin Ağ Üzerinde İlerlemesi

Bir kullanıcı tarayıcıya **[www.example.com](http://www.example.com)** yazdığında veri şu şekilde ilerler:

1. Uygulama katmanı isteği oluşturur.
2. Transport katmanı veriyi segmentlere ayırır (TCP/UDP).
3. Network katmanı hedef IP adresini ekler.
4. Data Link katmanı kaynak ve hedef MAC adreslerini ekler.
5. Physical katmanı veriyi kablo veya Wi-Fi üzerinden iletir.
6. Hedef cihazda veri aynı katmanlardan ters sırayla geçerek uygulamaya ulaşır.

Bu sürece **Encapsulation (Kapsülleme)** ve hedef tarafta **Decapsulation (Kapsülden Çıkarma)** denir.

## Kısaca

* **OSI Modeli**: Ağ iletişimini anlamak için kullanılan **7 katmanlı referans modelidir.**
* **TCP/IP Modeli**: İnternet üzerinde kullanılan **4 katmanlı ağ modelidir.**
* Veriler gönderilirken her katmanda farklı bilgiler eklenir ve hedef cihaza ulaştığında bu bilgiler sırayla çıkarılır.
