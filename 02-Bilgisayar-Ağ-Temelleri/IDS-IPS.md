# IDS ve IPS

IDS (Intrusion Detection System) ve IPS (Intrusion Prevention System), ağ ve sistemleri siber saldırılara karşı korumak için kullanılan güvenlik teknolojileridir.

Her ikisi de ağ trafiğini analiz eder ancak çalışma şekilleri farklıdır.

---

# IDS (Intrusion Detection System)

IDS, ağ veya sistem üzerindeki trafiği izleyerek şüpheli aktiviteleri tespit eden güvenlik sistemidir.

Bir saldırı algıladığında bunu raporlar veya alarm üretir, ancak trafiği engellemez.

## IDS Ne İşe Yarar?

* Ağ trafiğini sürekli izler.
* Şüpheli aktiviteleri tespit eder.
* Güvenlik uyarıları oluşturur.
* Log kayıtları tutar.

## Avantajları

* Ağdaki saldırıları hızlı şekilde tespit eder.
* Güvenlik ekiplerini bilgilendirir.
* Olay analizi için kayıt sağlar.

## Günlük Hayattan Örnek

Bir güvenlik kamerasını düşünün.

Kamera şüpheli bir kişiyi görür ve güvenlik görevlisini uyarır; ancak kişiyi durduramaz.

## Kısaca

**IDS, saldırıları tespit eden ve alarm oluşturan güvenlik sistemidir.**

---

# IPS (Intrusion Prevention System)

IPS, ağ trafiğini analiz ederek zararlı aktiviteleri tespit eden ve saldırıları otomatik olarak engelleyen güvenlik sistemidir.

IDS'den farklı olarak yalnızca tespit etmekle kalmaz, saldırıya anında müdahale eder.

## IPS Ne İşe Yarar?

* Ağ trafiğini analiz eder.
* Zararlı paketleri engeller.
* Şüpheli bağlantıları sonlandırır.
* Güvenlik politikalarını uygular.

## Avantajları

* Saldırıları otomatik olarak durdurur.
* Ağın güvenliğini artırır.
* Zararlı trafiğin hedef sisteme ulaşmasını engeller.

## Günlük Hayattan Örnek

Bir güvenlik görevlisini düşünün.

Şüpheli bir kişiyi fark ettiğinde sadece haber vermek yerine binaya girişini de engeller.

## Kısaca

**IPS, saldırıları tespit eden ve otomatik olarak engelleyen güvenlik sistemidir.**

---

# IDS ve IPS Arasındaki Fark

| IDS                      | IPS                                  |
| ------------------------ | ------------------------------------ |
| Saldırıları tespit eder. | Saldırıları tespit eder ve engeller. |
| Alarm üretir.            | Alarm üretir ve müdahale eder.       |
| Trafiği durdurmaz.       | Zararlı trafiği engeller.            |
| Pasif çalışır.           | Aktif çalışır.                       |

## Özet

* **IDS (Intrusion Detection System):** Saldırıları **tespit eder** ve güvenlik ekibini uyarır.
* **IPS (Intrusion Prevention System):** Saldırıları **tespit eder**, ardından **otomatik olarak engeller**.
