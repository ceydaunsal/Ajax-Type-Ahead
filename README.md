# 🔍 AJAX Type-Ahead

Bu proje, kullanıcı bir metin girdiğinde eşleşen şehir ve eyaletleri gerçek zamanlı olarak gösteren bir JavaScript uygulamasıdır. AJAX ile harici bir JSON verisinden veri çekerek çalışır.

## 🚀 Özellikler

- 📡 Harici bir JSON kaynağından şehir ve eyalet bilgilerini çeker.
- 🔎 Kullanıcının girdiği kelimeye göre anlık arama yapar.
- 🎨 Eşleşen kelimeleri vurgular.
- ⚡ Gerçek zamanlı olarak öneri listesi oluşturur.

## 🛠 Kullanılan Teknolojiler

- **HTML**: Arama kutusu ve sonuç listesini oluşturmak için.
- **CSS**: Liste elemanlarını ve vurgulamaları stilize etmek için.
- **JavaScript**: AJAX ile veri çekmek ve filtreleme işlemlerini yapmak için.

## 🔧 Nasıl Çalışır?

- 🌐 **Veri Çekme (AJAX & Fetch API)**

  JavaScript, `fetch()` metodunu kullanarak harici bir JSON dosyasından veri çeker.

- 🔎 **Gerçek Zamanlı Arama**

  Kullanıcının girdiği kelimeye uygun şehir ve eyaletleri filtreler.

- 🎨 **Kelimeyi Vurgulama**

  Kullanıcının girdiği kelimeyi, sonuç listesinde farklı bir renk ile vurgular.

- 📋 **Sonuçları Listeleme**

  Eşleşen şehir ve eyaletleri HTML içinde dinamik olarak listeler.

## 🎭 Örnek Kullanım

1. Arama kutusuna "New" yazarsanız **New York** ve **New Jersey** gibi şehirler gösterilir.
2. Kelimenin geçtiği kısımlar vurgulanır: `**New** York`.

Bu proje, dinamik arama ve AJAX kullanımı hakkında temel bir örnek sunmaktadır.
