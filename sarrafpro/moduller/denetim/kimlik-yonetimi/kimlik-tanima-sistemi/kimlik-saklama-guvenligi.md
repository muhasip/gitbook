---
description: TC Kimlik Kartlarının dosyalarını nasıl saklıyoruz?
cover: >-
  https://images.unsplash.com/photo-1544197150-b99a580bb7a8?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw5fHxzZXJ2ZXJ8ZW58MHx8fHwxNzQ2MTIyMTMxfDA&ixlib=rb-4.0.3&q=85
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
  tags:
    visible: true
  actions:
    visible: true
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
