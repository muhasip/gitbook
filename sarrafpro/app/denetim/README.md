---
description: >-
  Müşteri kimliklerini yükleyerek bilgileri otomatik tanıyan ve işlemlere hazır
  hale getiren özelliktir.
icon: fingerprint
cover: >-
  https://images.unsplash.com/photo-1517048676732-d65bc937f952?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw3fHxidXNzaW5lc3xlbnwwfHx8fDE3NDYzOTYxMTB8MA&ixlib=rb-4.0.3&q=85
coverY: 0
---

# Denetim

Müşterilerin kimlik tespit ve denetimlerini yapabilirsiniz.

WhatsApp hattınıza gönderilen kimlikler otomatik okunur.

Kimlikten okunan bilgiler ve doğrulama sistemi;

{% stepper %}
{% step %}
### Kimlik Kartının okunması

1. TC Kimlik No
2. Ad Soyad
3. Kimlik Seri No
4. Doğum Tarihi
5. Kimlik Geçerlilik Tarihi
{% endstep %}

{% step %}
### Kimlik Kartı Doğrulaması

NVI üzerinden kimliğin geçerli ve doğruluğu resmi olarak sorgulanır.
{% endstep %}

{% step %}
### MASAK Sorgusu

MASAK'ta yayınlanan Malvarlığı Dondurulanlar sorgusu yapılır.
{% endstep %}

{% step %}
### Loglama

TC Kimlik ile banka üzerindeki hareket Loglanarak sonraki işlemler için 2. aşamadaki süreç ile başlamak üzere kayıt edilir.
{% endstep %}

{% step %}
### Belgelendirme

İmzalanması için kimlik, dekont ve şablonlar ile oluşturduğunuz diğer bilgilerin çıktı almanız için hazır hale getirilir.
{% endstep %}
{% endstepper %}

{% hint style="danger" %}
TC Kimlik No sisteminizde veya [topluluk](../../uygulamalar/topluluk/ "mention") taki Tanıma sisteminde kayıtlı ise ve Kimlik Kartı geçerli ise süreç 3.aşamadan başlayarak hızlı bir şekilde devam eder.
{% endhint %}



{% hint style="info" %}
[Broken link](broken-reference "mention") modülü alt yapısını kullanmaktadır.
{% endhint %}
