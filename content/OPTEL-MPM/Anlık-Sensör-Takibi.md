---
title: "Anlık Sensör Takibi"
date: 2021-08-17T14:50:30+03:00
---


Geleneksel olarak üreticiler, özellikle karmaşık ve uzun çözümler üretenler olmak üzere, ürünün servis ve bakım zorluğuyla yüzleşme zorluğuyla karşılaşıyorlardı. Ancak IoT ile birlikte şu anda cihazlara entegre edilmiş iyi sensörler, ürün performansını gözlemlemek için onların kontrolünü sağlayan üreticilere bilgi akışı sağlıyor. Optoel MPM yazılımı tüm Iot sensörlerini gerçek zamanlı izlemeye olanak sağlamaktadır.


{{<mermaid align="left">}}
graph LR;
    A[Makine] -->|TCP&Serial Port| B(Sensör Verileri)
    B --> C{Karar Desktek Mekanizması}
    C -->|Web| D[Optoel MPM]
    C -->|E-mail| E[Rapor]
{{< /mermaid >}}