# NSArgument - Proje Kuralları

## Dil
- Bu proje Türkçe yazılmaktadır. Tüm iletişim ve içerik Türkçe olmalıdır.

## Dosya Yapısı
- `argument.md` — Ana argüman metni
- `TODO.md` — Sprint board ve yapılacaklar listesi
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
