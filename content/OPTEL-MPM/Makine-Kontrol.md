---
title: "Makine Kontrol"
date: 2021-08-17T14:50:14+03:00
---

{{< mermaid >}}
sequenceDiagram
    Makine->Donanım: Sensör
    loop 
        Donanım-->Makine: Parametreler Okunur.
    end
    Donanım->Karar Destek Mekanizması: Veriler İşlenir
    loop
        Karar Desktek Mekanizması->OPTOEL MPM: Verilerin Görselleştirilir.
    end
{{< /mermaid >}}

Üretim aşamalarında verimlilik ve maliyet yönetiminin ana unsurlarındandır. OPTOEL MPM İmalat Yönetim Sistemi, üretim aşamalarında ürün ağacında tanımlı bileşenlere uygulanacak işlemlerin operasyonel, makine bazlı olarak takibini ve süre bazlı maliyetlendirilmesini sağlar. Makine arıza, bakım, verimlilik, çalışma süreleri vb. işlemlerin takibini yapabilirsiniz.

OPTOEL MPM İmalat Yönetim Sistemi tarafından geçiştirilen Operasyon ve Makine Yönetimi modülü, üretim aşamalarının en verimli ve kontrollü bir şekilde gerçekleştirilmesini sağlar. Üretim aşamalarında üretim birimlerinin operasyon ve/veya makine bazlı iş emri bilgilerini görerek kontrollü üretim yapmasını sağlayabilirsiniz.

## Operasyon Tanımlama
Operasyona ait süre ve maliyet bilgilerinin tanımlanması üretim maliyetiniz ve verimlilik açısından önemlidir. OPTOEL MPM, operasyon için gerekli bilgilerin yönetimini hızlı ve yönetilebilir olarak sağlamaktadır. Operasyonların etkin kullanımı teslim sürelerinin belirlenmesi, maliyet iyleştirmelerinde fayda sağlayacaktır.

## Operasyon Makine Bağlantısı
Makineler operasyonların vazgeçilmez unsurlarıdır. Bir operasyon makine bağlantısı var ise operasyon verimlilik ve fiyat uygulaması makine üzerinden hesaplanmaktadır. OPTOEL MPM ile sabit ve makine bağlantılı operasyon bağlantıları oluşturabilirsiniz.

## Operasyon Detay Kayıtları Tanımlama
Üretiminiz operatörünüze bağlı kalmasın. Reçete tanımlama sırasında operasyon için önemli olan bilgileri tanımlamanızı ve almanızı sağlar. Operasyon yapım aşamalarında sizin için gerekli olan tanımlamaları siz yapın, biz sizin için takip edelim.

## Operasyon Hareket Kayıtları
Operasyon bazlı üretim yapan firmaların en büyük sorunları ürün için hangi operasyon yapılmış, hangileri bekliyor durumudur. OPTOEL MPM ürününüz için operasyonel bazlı takip imkânı sunar. Ürününüzün operasyonel durumunu anında görebilir ve bilgi alabilirsiniz.

## Makine Tanımlama
Makineler, operasyon kayıtlarının vazgeçilmez unsurlarıdır. Üretimin verimlilik ve maliyetine direkt etki eden makineler için gerekli bilgilerin alınması gerekmektedir. Makineye ait süre, birim fiyat ve çalışma zamanı girişlerini yapabilirsiniz. Makineler için genel verimlilik ve doluluk oranlarınızı görebilirsiniz.

## Çalışma Periyodu Tanımlama
Makinelerin çalışma performanslarını tanımlamak makine verimliliği konusunun vazgeçilmezidir. Makineler için hızlı ve kolay şekilde tarih bazlı olarak çalışma saat aralığı tanımlayabilir ve çalışma saatlerini yönetebilirsiniz.

## Arıza / Bakım Yönetimi
Makinenin arıza ve bakım işlemleri firmalar açısından en dikkat edilmesi gereken ve oldukça maliyetli bir durumdur. Makinelerinizin bakım kayıtlarını oluşturabilir ve bakım zamanını takip edebilirsiniz. Operatörler tarafından girilen arıza kayıtlarını inceleyebilir ve bu konuda önlemler alabilirsiniz.

## Makine Kullanıcı Tanımlama
Her makinenin kullanımı için bir belge ve ustalık gerekebilir. Makine kullanımınızı kullanıcıya bağlayabilir ve makine için gerekli kullanım kısıtlamasını sağlayabilirsiniz. Operatörlerinizin kullandıkları makine bazlı verimliliklerini takip edebilirsiniz.