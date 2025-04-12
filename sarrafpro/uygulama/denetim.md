---
description: >-
  Müşteri kimliklerini yükleyerek bilgileri otomatik tanıyan ve işlemlere hazır
  hale getiren özelliktir.
icon: fingerprint
coverY: 0
layout:
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
TC Kimlik No sisteminizde veya [topluluk](../workspace/topluluk/ "mention") taki Tanıma sisteminde kayıtlı ise ve Kimlik Kartı geçerli ise süreç 3.aşamadan başlayarak hızlı bir şekilde devam eder.
{% endhint %}



{% hint style="info" %}
[musteriler.md](../on-muhasebe/cari-kartlari/musteriler.md "mention") modülü alt yapısını kullanmaktadır.
{% endhint %}
