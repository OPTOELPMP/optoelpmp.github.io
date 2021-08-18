---
title: "Kullanıcı Yetkilendirme"
date: 2021-08-17T14:50:54+03:00
---

![Kalite Kontrol1](https://erelbi.github.io/test-optoel/images/kullanıcı-yönetimi.png)

* MPM sistemlerinde kullanıcı yetkilerinin doğu bir şekilde tanımlanması ve sisteme entegre edilmesi çok önemlidir. 
* Böylece sadece görevli ve ilgili kişiler işlemleri yapabilecek, görevlilerin arasındaki sınır korunacak ve görevler ayrılığı prensibi (segregation of duties – SOD) uygulanabilecektir.

MPM uygulamalarında, projenin bazı aşamalarında test bazlı ya da doğru tanımlama yapılmadan verilen kullanıcı hakları, sistem canlı olarak kullanılmaya başlandığında bazı güvenlik riskleri içermektedir. Bu durum, canlı sisteme geçiş öncesinde kullanıcı haklarının listelenip, standartlara göre çakışmalarını belirleyecek programlar ile kullanıcı haklarının gözden geçirilmesini sağlayacaktır. Böylece sistemin güvenlik düzeyi artacaktır. Bununla birlikte yetkili kullanıcı (superuser) haklarının verildiği kullanıcıların da doğru kişiler olarak belirlenmesi çok önemlidir.