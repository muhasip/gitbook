---
description: >-
  Fiziksel veya Sanal POS hareketlerinin faturalandırma işlemlerine
  hazırlanacağı bir özelliktir.
icon: file-invoice
cover: >-
  https://images.unsplash.com/photo-1537724326059-2ea20251b9c8?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw5fHxjcmVkaXQlMjBjYXJkfGVufDB8fHx8MTc0NjM5NTk0MHww&ixlib=rb-4.0.3&q=85
coverY: 0
layout:
  width: default
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
  metadata:
    visible: false
---

# Hızlı Fatura

## POS İşlem Resmileştirme

POS (Point of Sale) işlemleri, ticari satışların fiili gerçekleştiği andan itibaren **resmiyet ve kayıt gerektiren** finansal aktivitelerdir.\
SarrafPro ile bu işlemleri **uyumlu, izlenebilir ve denetime hazır** şekilde yönetirsiniz.

### Ne Demek “Resmileştirme”?

Resmileştirme, POS işleminin:

* **Doğru bir şekilde kaydedilmesi**
* **Belgelendirilmesi**
* **Denetim sistemine entegre edilmesi**

… anlamına gelir.

Bu süreç manuel not alma yerine sistematik şekilde **otomatik kayıt + doğrulama + raporlama** demektir.

### Neden Önemli?

* MASAK, vergi ve denetim otoriteleri POS verilerinin **izlenebilirliğini** talep eder.
* Eksik veya yanlış POS kayıtları **uyum riskini** artırır.
* SarrafPro tüm POS işlemlerini merkezi **denetim kaydına** dahil eder.

### Süreç Adımları

1. **POS işlem alımı**
   * Terminalden veya API ile gelen işlem verisi.
2. **Veri standardizasyonu**
   * Tutar, tarih, saat, mağaza/terminal ID’si.
3. **Kimlik & müşteri ilişkisi**
   * Gerekirse işlem müşteri profili ile eşlenir.
4. **Doğrulama & onay**
   * Kurallara göre otomatik kontrol.
5. **Arşivleme & raporlama**
   * Denetime hazır formatlarda çıktı.

### Ne Kayıt Edilir?

| Alan               | Açıklama              |
| ------------------ | --------------------- |
| Tarih / Saat       | İşlem zamanı          |
| Tutar              | Brüt / net            |
| Mağaza / Terminal  | POS konumu            |
| İşlem Tipi         | Satış / iade / iptal  |
| Müşteri Bağlantısı | Varsa müşteri profili |

### Denetim Bağlamı

SarrafPro, POS işlemlerini:

* **Zaman damgası ile**
* **Çift taraflı denetim kayıtlarıyla**
* **PDF/Excel raporlarıyla**

… denetime hazır şekilde tutar.

### İpucu

POS işlemlerini günlük veya saatlik **mutabakat raporuna** dahil etmek, riskleri anında görmenizi sağlar.
