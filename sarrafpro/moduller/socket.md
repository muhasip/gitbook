---
description: SarrafPro Socket bu süreci kurumsal bir altyapıya dönüştürür.
icon: circles-overlap
---

# Socket

## SarrafPro Socket Modülü

SarrafPro Socket, kuyumcu işletmelerinde oluşan finansal kayıtların resmi muhasebe programlarına eksiksiz, düzenli ve izlenebilir şekilde aktarılmasını sağlayan entegrasyon modülüdür.

Kuyumculuk sektöründe satış, tahsilat, banka hareketi, e-Fatura, e-Arşiv, iade, düzeltme, cari hareket ve kasa işlemleri birbirinden kopuk ilerlediğinde muhasebe tarafında ciddi veri kaybı oluşur. Bu durum hem operasyonel hatalara hem de denetim süreçlerinde açıklanamayan kayıt farklarına neden olabilir.

SarrafPro Socket bu problemi çözmek için geliştirilmiştir.

Modülün temel amacı şudur:

> SarrafPro’da oluşan tüm ticari ve finansal kayıtları, muhasebe programlarına eksiksiz, standart ve denetlenebilir formatta aktarmak.

***

### SarrafPro Socket Ne İşe Yarar?

SarrafPro Socket, SarrafPro ile işletmenin kullandığı muhasebe programı arasında veri aktarım köprüsü kurar.

Bu köprü sayesinde SarrafPro üzerinde oluşan kayıtlar manuel olarak tekrar girilmez. Satış, tahsilat, fatura, banka hareketi ve cari işlem kayıtları muhasebe sistemine aktarılabilir hale gelir.

Böylece işletme içinde aynı veri tekrar tekrar işlenmez.

Bu yapı özellikle şu alanlarda kritik önem taşır:

* Satış kayıtlarının muhasebeye aktarılması
* Banka hareketlerinin ilgili kayıtlarla eşleştirilmesi
* e-Fatura ve e-Arşiv belgelerinin muhasebe sistemine taşınması
* Cari hesap hareketlerinin doğru aktarılması
* İade, iptal ve düzeltme kayıtlarının muhasebede izlenmesi
* Denetim için kayıt zincirinin korunması

***

### Neden Socket Modülüne İhtiyaç Var?

Kuyumculukta muhasebe aktarımı klasik ticaret işletmelerine göre daha hassastır.

Çünkü kuyumcu işletmelerinde sadece TL bazlı satış yoktur. İşlemler çoğu zaman altın, döviz, gram, has, işçilik, kur farkı, banka tahsilatı ve fatura kayıtlarıyla birlikte ilerler.

Yanlış veya eksik aktarılan bir kayıt şu sorunlara neden olabilir:

* Muhasebe kayıtlarında cari fark oluşması
* Banka tahsilatı ile satış kaydının eşleşmemesi
* Fatura ile ödeme arasında açıklanamayan fark kalması
* İade ve düzeltme işlemlerinin eksik görünmesi
* Denetimde işlem zincirinin kopması
* MASAK ve vergi süreçlerinde açıklama yükünün artması

SarrafPro Socket, bu riskleri azaltmak için kayıtları tek tek değil, işlem zinciri mantığıyla ele alır.

Yani sadece “satış kaydı” aktarılmaz.

Satışın bağlı olduğu tahsilat, banka hareketi, fatura, cari hesap ve düzeltme bilgileri de aktarım senaryosuna dahil edilir.

***

### Eksiksiz Aktarım Ne Anlama Gelir?

SarrafPro Socket tarafında “eksiksiz aktarım”, SarrafPro’da muhasebe aktarım kapsamına giren tüm kayıtların belirlenen kurallara göre muhasebe programına iletilmesi anlamına gelir.

Bu kapsamda aktarılabilecek başlıca kayıt türleri şunlardır:

* Satış kayıtları
* Alış kayıtları
* Tahsilat kayıtları
* Ödeme kayıtları
* Banka hareketleri
* Cari hesap hareketleri
* e-Fatura kayıtları
* e-Arşiv kayıtları
* İade işlemleri
* İptal işlemleri
* Düzeltme kayıtları
* Kasa hareketleri
* Şube bazlı finansal kayıtlar
* Kullanıcı işlem logları
* Mutabakat kayıtları

Bu yapı sayesinde işletme, SarrafPro’da oluşan operasyonel kaydı muhasebe tarafında tekrar üretmek zorunda kalmaz.

Veri bir kez oluşur, doğru yere aktarılır.

***

### Hangi Veriler Muhasebe Programına Aktarılır?

SarrafPro Socket modülü, işletmenin ihtiyaçlarına ve kullanılan muhasebe programının desteklediği yapıya göre farklı veri setlerini aktarabilir.

#### 1. Satış Kayıtları

Satış işlemlerinde ürün, tutar, ödeme tipi, müşteri bilgisi, fatura durumu ve işlem zamanı aktarılabilir.

Aktarılabilecek örnek bilgiler:

* Satış numarası
* Satış tarihi
* Müşteri bilgisi
* Ürün veya hizmet bilgisi
* Tutar
* KDV bilgisi
* Ödeme tipi
* Fatura durumu
* Şube bilgisi
* İşlemi yapan kullanıcı

***

#### 2. Tahsilat ve Ödeme Kayıtları

Kuyumcu işletmelerinde satış ile tahsilat her zaman aynı anda kapanmayabilir. Havale, EFT, nakit, kredi kartı veya parçalı ödeme senaryoları olabilir.

SarrafPro Socket bu kayıtları muhasebeye aktarılabilir hale getirir.

Aktarılabilecek örnek bilgiler:

* Tahsilat tarihi
* Ödeme yöntemi
* Banka hesabı
* Tutar
* Para birimi
* Cari hesap eşleşmesi
* Açıklama
* Referans numarası

***

#### 3. Banka Hareketleri

SarrafPro’nun banka entegrasyonu üzerinden alınan hareketler, Socket modülüyle muhasebe sistemine aktarılabilir.

Bu noktada sadece banka hareketinin kendisi değil, hareketin hangi satış veya cari kayıtla eşleştiği de önemlidir.

Aktarılabilecek bilgiler:

* Banka adı
* Hesap bilgisi
* İşlem tarihi
* Gelen/giden tutar
* Açıklama
* Gönderen/alıcı bilgisi
* IBAN
* Referans numarası
* Eşleşen satış veya cari kayıt
* Risk kontrol sonucu

***

#### 4. e-Fatura ve e-Arşiv Kayıtları

SarrafPro üzerinde oluşturulan veya eşleşen e-Fatura ve e-Arşiv kayıtları muhasebe programına aktarılabilir.

Aktarılabilecek bilgiler:

* Fatura numarası
* Fatura tarihi
* Alıcı bilgisi
* Vergi/TCKN bilgisi
* Mal/hizmet satırları
* KDV bilgileri
* Toplam tutar
* Belge tipi
* Fatura durumu
* İptal/iade/düzeltme bilgileri

***

#### 5. Cari Hesap Hareketleri

Kuyumcu işletmelerinde cari hesap yönetimi kritik önemdedir. Müşteri, tedarikçi, toptancı ve şube bazlı hareketler muhasebe tarafında doğru izlenmelidir.

SarrafPro Socket ile cari hareketler muhasebe programına aktarılabilir.

Aktarılabilecek bilgiler:

* Cari kart bilgisi
* Borç/alacak hareketi
* İşlem tarihi
* Açıklama
* Para birimi
* Bağlı fatura
* Bağlı tahsilat
* Şube bilgisi

***

### Muhasebe Aktarımında Kayıt Zinciri

SarrafPro Socket sadece veri göndermez.

Kayıtların birbirleriyle ilişkisini de korur.

Örneğin bir satış işlemi şu zincirle ilerleyebilir:

1. Satış kaydı oluşur.
2. Müşteri veya cari hesap eşleşir.
3. Tahsilat banka hareketiyle kapanır.
4. e-Fatura veya e-Arşiv kaydı oluşturulur.
5. İşlem muhasebe programına aktarılır.
6. Aktarım sonucu loglanır.
7. Hata varsa tekrar aktarım kuyruğuna alınır.

Bu yapı sayesinde bir işlem, sadece tek satırlık muhasebe kaydı olarak değil, denetlenebilir bir işlem zinciri olarak yönetilir.

***

### Manuel Veri Girişini Azaltır

Kuyumcularda en büyük operasyonel sorunlardan biri aynı verinin farklı sistemlere tekrar girilmesidir.

Satış ayrı yerde, banka ayrı yerde, fatura ayrı yerde, muhasebe ayrı yerde tutulduğunda hata kaçınılmaz olur.

SarrafPro Socket bu tekrarları azaltır.

Muhasebe personeli veya işletme sahibi aynı kaydı ikinci kez girmek zorunda kalmaz. Bu da hem zaman kazandırır hem de hatalı kayıt riskini düşürür.

***

### Denetime Hazır Aktarım Mantığı

SarrafPro Socket, muhasebe aktarımını sadece teknik bir veri transferi olarak görmez.

Her aktarım işleminde şu bilgiler kayıt altında tutulur:

* Hangi kayıt aktarıldı?
* Ne zaman aktarıldı?
* Hangi muhasebe sistemine gönderildi?
* Aktarım başarılı mı?
* Hata oluştuysa sebebi ne?
* Aktarım tekrarlandı mı?
* İşlemi kim tetikledi?
* Otomatik mi manuel mi aktarıldı?

Bu yapı, işletmenin geriye dönük kontrol yapabilmesini sağlar.

Denetim, mutabakat ve iç kontrol süreçlerinde “bu kayıt muhasebeye aktarıldı mı?” sorusunun cevabı sistem üzerinden görülebilir.

***

### Hata Yönetimi ve Tekrar Aktarım

Muhasebe aktarım süreçlerinde her zaman teknik hata, bağlantı sorunu veya veri formatı uyumsuzluğu yaşanabilir.

SarrafPro Socket bu durumlar için hata yönetimi mantığıyla çalışır.

Olası hata senaryoları:

* Muhasebe programı bağlantı hatası
* Eksik cari bilgisi
* Vergi numarası format hatası
* Fatura satırı uyumsuzluğu
* Banka hareketi eşleşme hatası
* Para birimi uyumsuzluğu
* Daha önce aktarılmış kayıt uyarısı

Bu hatalar sistemde izlenebilir.

Yetkili kullanıcı, başarısız aktarımları görebilir, gerekli düzeltmeyi yapabilir ve aktarımı tekrar başlatabilir.

***

### Muhasebe Programlarıyla Entegrasyon Yaklaşımı

SarrafPro Socket, işletmenin kullandığı muhasebe programına göre farklı aktarım yöntemlerini destekleyecek şekilde tasarlanmıştır.

Desteklenebilecek aktarım yöntemleri:

* API ile doğrudan aktarım
* XML aktarımı
* Excel/CSV aktarımı
* Muhasebe fişi formatında dışa aktarım
* Cari kart aktarımı
* Fatura aktarımı
* Banka hareketi aktarımı
* Toplu aktarım
* Zamanlanmış otomatik aktarım

Kullanılan muhasebe programının teknik kabiliyetine göre entegrasyon modeli belirlenir.

Amaç nettir:

> SarrafPro’da oluşan kayıtların resmi muhasebe programlarına temiz, düzenli ve eksiksiz şekilde aktarılması.

***

### Kimler İçin Uygundur?

SarrafPro Socket özellikle şu işletmeler için uygundur:

* Çok sayıda banka hesabı kullanan kuyumcular
* e-Fatura ve e-Arşiv süreçlerini dijital yöneten işletmeler
* Muhasebe kayıtlarını manuel girmek istemeyen firmalar
* Şube bazlı satış ve tahsilat yapan kuyumcular
* Muhasebecisiyle düzenli veri paylaşan işletmeler
* Denetim ve mutabakat süreçlerini güçlendirmek isteyen firmalar
* MASAK ve GİB süreçlerinde kayıt bütünlüğüne önem veren işletmeler

***

### SarrafPro Socket’in İşletmeye Katkısı

SarrafPro Socket, muhasebe sürecini hızlandırırken kontrolü de artırır.

Başlıca faydalar:

* Manuel veri girişini azaltır.
* Muhasebe hatalarını düşürür.
* Banka, satış ve fatura kayıtlarını aynı zincirde tutar.
* Cari hesap mutabakatını kolaylaştırır.
* Denetim süreçleri için izlenebilirlik sağlar.
* Aktarım hatalarını kayıt altına alır.
* Eksik belge ve kayıt farklarını azaltır.
* Şube ve kullanıcı bazlı kontrol sağlar.
* Muhasebe programına düzenli veri akışı oluşturur.

***

### SarrafPro Socket Nasıl Çalışır?

SarrafPro Socket genel olarak şu akışla çalışır:

1. SarrafPro’da işlem kaydı oluşur.
2. Kayıt türü belirlenir.
3. Muhasebe aktarım kuralları çalışır.
4. Gerekli eşleştirmeler yapılır.
5. Veri muhasebe programına uygun formata dönüştürülür.
6. Aktarım yapılır.
7. Aktarım sonucu loglanır.
8. Başarısız aktarım varsa hata kuyruğuna alınır.
9. Gerekirse tekrar aktarım yapılır.

Bu yapı hem otomatik hem kontrollü aktarım senaryolarını destekler.

***

### Otomatik ve Kontrollü Aktarım

Her işletmenin muhasebe süreci aynı değildir.

Bazı işletmeler kayıtların otomatik aktarılmasını isterken, bazıları muhasebe aktarımı öncesinde kontrol ve onay mekanizması kullanmak isteyebilir.

SarrafPro Socket iki senaryoyu da destekleyecek şekilde kurgulanır:

#### Otomatik Aktarım

Belirlenen kurallara uyan kayıtlar otomatik olarak muhasebe sistemine aktarılır.

Örnek:

* Gün sonu satışları
* Onaylanmış faturalar
* Eşleşmiş banka tahsilatları
* Cari hesap hareketleri

#### Kontrollü Aktarım

Yetkili kullanıcı aktarım öncesinde kayıtları inceler ve onaylar.

Örnek:

* Yüksek tutarlı işlemler
* Riskli müşteri kayıtları
* Eşleşmemiş banka hareketleri
* Eksik belge içeren işlemler
* Düzeltme ve iade kayıtları

Bu yapı, hız ile kontrol arasında doğru dengeyi kurar.

***

### MASAK, GİB ve Muhasebe Süreçleri İçin Kayıt Bütünlüğü

SarrafPro Socket, tek başına bir muhasebe programı değildir.

Muhasebe programlarının yerine geçmez.

Görevi, SarrafPro’da oluşan finansal ve operasyonel kayıtları muhasebe sistemlerine doğru şekilde aktarmaktır.

Bu nedenle modül, kayıt bütünlüğünü merkeze alır.

Kayıt bütünlüğü şu anlama gelir:

* Satış kaydı ayrı kalmaz.
* Tahsilat kaydı ayrı kalmaz.
* Banka hareketi kopuk kalmaz.
* Fatura bilgisi dışarıda kalmaz.
* Cari hareket izlenebilir olur.
* Aktarım sonucu kayıt altına alınır.

Bu yaklaşım, denetim süreçlerinde işletmenin elini güçlendirir.

***

### Sık Sorulan Sorular

#### SarrafPro Socket bir muhasebe programı mı?

Hayır. SarrafPro Socket bir muhasebe programı değildir. SarrafPro’da oluşan kayıtları işletmenin kullandığı resmi muhasebe programına aktarmak için kullanılan entegrasyon modülüdür.

#### Hangi kayıtlar muhasebeye aktarılır?

Satış, alış, tahsilat, ödeme, banka hareketi, cari hareket, e-Fatura, e-Arşiv, iade, iptal ve düzeltme kayıtları aktarım kapsamına alınabilir.

#### Aktarım tamamen otomatik mi çalışır?

İşletmenin tercihine göre otomatik veya kontrollü çalışabilir. Bazı kayıtlar doğrudan aktarılırken, riskli veya eksik verili kayıtlar onaya düşürülebilir.

#### Hata olursa ne olur?

Başarısız aktarımlar loglanır. Hata sebebi görüntülenir. Gerekli düzeltme yapıldıktan sonra kayıt tekrar aktarılabilir.

#### Banka hareketleri de muhasebeye aktarılır mı?

Evet. Banka hareketleri, ilgili satış, tahsilat veya cari kayıtlarla eşleştirildikten sonra muhasebe programına aktarılabilir.

#### e-Fatura kayıtları aktarılır mı?

Evet. e-Fatura ve e-Arşiv kayıtları, kullanılan muhasebe programının desteklediği formata göre aktarılabilir.

#### SarrafPro Socket denetim süreçlerine katkı sağlar mı?

Evet. Aktarılan kayıtlar, aktarım zamanı, aktarım sonucu ve hata geçmişi loglandığı için denetim ve mutabakat süreçlerinde izlenebilirlik sağlar.

***

###

SarrafPro Socket, kuyumcu işletmelerinin muhasebe aktarım sürecini düzenli, kontrollü ve denetlenebilir hale getirir.

Manuel veri girişini azaltır.\
Eksik kayıt riskini düşürür.\
Satış, banka, fatura ve cari hareketleri aynı zincirde tutar.\
Muhasebe programlarına düzenli ve eksiksiz veri aktarımı sağlar.

Kuyumculuk sektöründe finansal kayıtların doğru aktarılması sadece operasyonel kolaylık değildir.

Aynı zamanda güven, uyum ve denetim meselesidir.

