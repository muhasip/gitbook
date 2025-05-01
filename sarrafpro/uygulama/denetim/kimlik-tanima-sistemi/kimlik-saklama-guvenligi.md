---
description: TC Kimlik Kartlarının dosyalarını nasıl saklıyoruz?
layout:
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

# 🔐 Kimlik Saklama Güvenliği

## 🔐 AES-256-CBC Özeti

| Özellik             | Açıklama                                            |
| ------------------- | --------------------------------------------------- |
| Anahtar uzunluğu    | 256 bit (32 byte)                                   |
| Blok boyutu         | 128 bit (16 byte)                                   |
| IV (başlatıcı veri) | 128 bit (16 byte)                                   |
| Mod                 | CBC (Cipher Block Chaining)                         |
| Güvenli mi?         | Evet, doğru kullanıldığında                         |
| IV gerektiriyor mu? | Evet, **her şifreleme için farklı** IV kullanıyoruz |
