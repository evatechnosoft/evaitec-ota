# evaitec OTA — uygulama katalogu

Tum evaitec uygulamalarinin (NetMovies, rcmycar, wellness, evaitecOTA, evaglass...) ortak katalogu.
evaitecOTA ve uygulamalarin kendi guncelleyicisi `apps.json`'i buradan okur.

- Katalog: <https://evatechnosoft.github.io/evaitec-ota/apps.json>
- Indirme sayfasi: <https://evatechnosoft.github.io/evaitec-ota/>

| Dosya | Ne ise yarar |
|---|---|
| `apps.json` | Uygulama listesi: surum, `downloadUrl`, `mirrors` (ev aynasi once), `sha256`. |
| `index.html` | Indirme sayfasi, `apps.json`'i okur. |
| `assets/` | Ikonlar. |

Yayin betikleri yalnizca bu depoya yazar. APK dosyalari her uygulamanin kendi release'inde durur
(`downloadUrl`). Eski adres `evaglass-releases/apps.json` kurulu eski istemciler icin oradaki
zamanlanmis is (`.github/workflows/katalog-kopyala.yml`) ile bu dosyadan kopyalanir; ona elle yazma.

Sema ayrintisi: `evaglass-releases/README.md` (ayni sema).
