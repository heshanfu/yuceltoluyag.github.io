---
layout:  post
title: linux httrack kullanımı
description: linux httrack kullanımı
tags:
-  ipucu
comments:  true
edit_url:  true
---

Merhaba, httrack websitelerini internetiniz yokken kullanmak amaçlı üretilmiş bir yazılımdır. Windows tarafında sıkça kullandığım bu yazılımın linux tarafında terminal üzerinden nasıl kullanılacağı ile ilgili bir döküman hazırlamak istedim.

```sh
sudo apt-get install httrack #programı kuruyoruzEnter project name : #projenin ismiBase path (return=/home/baba/websites/) : : #projenin indirileceği dizinEnter URLs (separated by commas or blank spaces) : #Kaydedeceğiniz websitesinin adresi
```

Action (enter) Kısmında ki menüler ise şöyle :

-   Siteyi Kopyala
-   Siteyi sihirbaz yöneticisi ile kopyala
-   Sadece dosyaları çek
-   Tüm linklerin bir kopyasını çek(yanlışta biliyor olabilirim kullanmadım)
-   Bookmark testi uygula
-   Çıkış

Daimi olarak 1 numarayı kullanıyorum diğerlerini kullanma ihtiyacı hissetmedim. Bazı websiteleri httrack karşı önlem almış olabilir. Her urlyi çekeceksiniz diye bir kaide yok :) Çevrim dışı olarak indirdiğiniz siteyi mutlaka sağ tık -> öğeyi incele menüsünden muhakkak inceleyiniz. Eğer kırmızıyla yazılmış yazılar görüyor iseniz onları düzeltmeniz gerekebilir.

3. [Video Link](https://www.youtube.com/channel/UCJyK4D5BcoPXjV5T8N8-liA?view_as=subscriber)