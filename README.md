# ABAP – Tarih Analizi ve Gün Raporu

Bu projede SAP ABAP ile sistem tarihi ve kullanıcı girişi üzerinden gün ve ay farkı hesaplaması yapılmıştır.  
Elde edilen tarih aralığı içerisindeki her günü, haftanın günlerine göre ekran üzerine hizalı olarak yazdıran bir algoritma geliştirilmiştir.

## Özellikler
- Sistem tarihini otomatik olarak parametreye atama
- Tarih farkı ve minimum gün sayısı kontrolü
- Haftanın günlerini indexleme
- Ayları özel Türkçe formatta yazma (MYS, HZN, TMZ vb.)
- Kullanıcıya görsel olarak gün gün liste sunumu

## Kazanımlar
- Tarih işlemleri (`sy-datum`, tarih farkı hesaplama)
- `LOOP AT SCREEN`, `MODIFY SCREEN` ile alan kontrolü
- `READ TABLE`, `CASE`, `WHILE` kullanımı
- Ekran çıktısında veri hizalama ve görsel düzen

