# NSArgument - Proje Kuralları

## Dil
- Bu proje Türkçe yazılmaktadır. Tüm iletişim ve içerik Türkçe olmalıdır.

## Dosya Yapısı
- `argument.md` — Ana argüman metni
- `TODO.md` — Sprint board ve yapılacaklar listesi
- `SOURCES.md` — Kaynak doğrulama dosyası (tüm kaynakların doğrulama durumu)
- `Faz2.md` — İkinci faz planlaması

## Dipnot ve Kaynak Bütünlüğü (Her Düzenlemede Kontrol Et)

Her `argument.md` düzenlemesinden sonra şu kontrolleri yap:

1. **Referans-tanım eşleşmesi:** Metin içinde kullanılan her `[^dipnot]` referansının dosya sonundaki `## Dipnotlar` bölümünde bir tanımı (`[^dipnot]:`) olmalı.
2. **Yetim tanımlar:** `## Dipnotlar` bölümünde tanımlı ama metin içinde hiç referanslanmamış dipnot olmamalı.
3. **İçerik-referans uyumu:** Dipnot referansı, bağlı olduğu metnin içeriğiyle anlamsal olarak uyuşmalı (yanlış dipnota bağlama/kayma olmamalı).
4. **Kaynakça tutarlılığı:** Dipnotlarda kullanılan kaynaklar `## Kaynakça` bölümünde de yer almalı.
5. **Duplikasyon kontrolü:** Aynı içerik bloğunun birden fazla yerde tekrarlanmadığından emin ol.

## Yazım Kuralları
- Akademik ton, tarafsız dil. "Kesinlikle kanıtlar" yerine "güçlü şekilde destekler" gibi ifadeler tercih et.
- Bilimsel iddialar kaynaklı olmalı — peer-reviewed makale veya standart bilim tarihi kaynağı.
- Karşı argümanları dürüstçe sun, straw-man yapma.
- **Araştırma sonucu yazılan her bilgi kaynaklı olmalı:** Metne yeni bir bilimsel, tarihsel veya akademik bilgi eklendiğinde mutlaka dipnot (`[^kaynak_adi]`) ve tanımı eklenecek. Kaynaksız iddia eklenmemeli.

## Kaynak Doğrulama Kuralları (SOURCES.md)

`SOURCES.md` dosyası tüm kaynakların doğrulama durumunu takip eder. Bu dosya kaynak güvenilirliğinin temel referansıdır.

1. **Her yeni kaynak eklenmesinde SOURCES.md de güncellenmeli:** `argument.md`'ye yeni bir dipnot veya kaynakça girişi eklendiğinde, aynı kaynak `SOURCES.md`'ye de uygun formatta eklenmeli.
2. **Her kaynak değişikliğinde SOURCES.md güncellenmeli:** Mevcut bir kaynağın bilgileri (DOI, sayfa numarası, iddia içeriği) değiştirildiğinde, `SOURCES.md`'deki ilgili giriş de güncellenmeli.
3. **Kaynak silme durumunda SOURCES.md güncellenmeli:** `argument.md`'den bir kaynak kaldırıldığında, `SOURCES.md`'deki ilgili giriş de kaldırılmalı veya "KALDIRILDI" olarak işaretlenmeli.
4. **Doğrulama durumu güncel tutulmalı:** Bir kaynak doğrulandığında `[DOGRULANDI]`, sorun tespit edildiğinde `[HATALI]` veya `[KISMI]` olarak güncellenmeli.
5. **Yanlış kaynak düzeltme zorunluluğu:** `[HATALI]` olarak işaretlenen kaynaklar öncelikli olarak düzeltilmeli. Yanlış bilgi argümanın güvenilirliğini doğrudan zedeler.
