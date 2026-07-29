# Load Balancer (Yük Dengeleyici) Nedir?

Load Balancer (Yük Dengeleyici), gelen ağ veya uygulama isteklerini birden fazla sunucu arasında dağıtarak sistemlerin daha verimli, hızlı ve kesintisiz çalışmasını sağlayan bir teknolojidir.

Temel amacı, tek bir sunucunun aşırı yüklenmesini önlemek ve hizmetin sürekli kullanılabilir olmasını sağlamaktır.

## Load Balancer Nasıl Çalışır?

1. Kullanıcı bir web uygulamasına istek gönderir.
2. İstek önce Load Balancer'a ulaşır.
3. Load Balancer, isteği en uygun sunucuya yönlendirir.
4. Sunucu isteği işler ve yanıtı kullanıcıya gönderir.

## Load Balancer Ne İşe Yarar?

* Gelen trafiği birden fazla sunucuya dağıtır.
* Sunucuların aşırı yüklenmesini önler.
* Performansı artırır.
* Yüksek erişilebilirlik (High Availability) sağlar.
* Bir sunucu çalışmazsa trafiği diğer sunuculara yönlendirir.

## Load Balancer Türleri

### Layer 4 (L4) Load Balancer

* TCP ve UDP trafiğini yönetir.
* IP adresi ve port bilgisine göre yönlendirme yapar.
* Daha hızlı çalışır.

### Layer 7 (L7) Load Balancer

* HTTP ve HTTPS trafiğini yönetir.
* URL, başlık (Header) ve çerez (Cookie) gibi uygulama katmanı bilgilerine göre yönlendirme yapabilir.
* Daha gelişmiş yönlendirme özellikleri sunar.

## Kullanım Alanları

* Web siteleri
* E-ticaret platformları
* Bulut ortamları
* Büyük kurumsal uygulamalar
* API servisleri

## Günlük Hayattan Örnek

Bir bankada birden fazla gişe olduğunu düşünün.

Müşteriler tek bir gişeye yönlendirilirse uzun kuyruk oluşur. Ancak görevli, müşterileri boş gişelere yönlendirirse işlemler daha hızlı tamamlanır.

Load Balancer da aynı mantıkla çalışır; gelen istekleri uygun sunucular arasında dağıtarak sistemin daha verimli çalışmasını sağlar.

## Kısaca

**Load Balancer, gelen istekleri birden fazla sunucu arasında dağıtarak performansı artıran ve hizmetin kesintisiz çalışmasını sağlayan sistemdir.**
