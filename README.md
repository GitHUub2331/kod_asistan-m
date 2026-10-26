# Projenin Adı: Kod-Asistan Basit Kayıt Akışı 

## Uygulamanın Amacı
Kullanıcıdan alınan birden fazla farklı metinsel veriyi (ad, soyadı vb.) mantıksal bir sıra dâhilinde işlemek, metin birleştirme operatörlerini kullanmak ve sonucunu standart akış şeması sembolleriyle tasarlamak.

## Problem Senaryosu
Kod-Asistan projesinin kullanıcı yönetim modülü tasarlanacaktır. Asistanın kullanıcıya ismiyle hitap edebilmesi ve sistemi kişiselleştirebilmesi için kayıt aşamasında ad ve soyadı verilerinin ayrı ayrı alınması, arka planda birleştirilerek tek bir profil kimliği haline getirilmesi gerekmektedir.

## Akış Adımları (Doğrusal Algoritma)
1. **Başlama:** Akışın başlatılması.
2. **İsim İsteme:** Kullanıcıdan ad bilgisinin alınması.
3. **Soyisim İsteme:** Kullanıcıdan soyad bilgisinin alınması.
4. **Metin Birleştirme:** Alınan verilerin operatörler yardımıyla birleştirilmesi.
5. **Selamlama Mesajı Gösterme:** Kişiselleştirilmiş mesajın kullanıcıya iletilmesi.
6. **Durma:** Akışın sonlandırılması
