# Annebek web sayfaları

Bu klasör herkese açık bir GitHub deposuna (ör. `miniktabak-web`) olduğu gibi yüklenir.
Depo > Settings > Pages > "Deploy from a branch" > `main` / `(root)`.

- `index.html`: tanıtım ve hesap silme (`#hesap-silme`)
- `gizlilik.html`: gizlilik politikası (Play Console'a bu adres girilir)
- `kosullar.html`: kullanım koşulları
- `ac.html`: paylaşım bağlantıları (`?u=<uzman>` / `?e=<etkinlik>`); uygulama yüklüyse açar, değilse mağaza düğmeleri. Elle düzenlenir.
- `ozet.html`: "Takip özetini paylaş" bağlantısı (`#<özet>`). Özet adresin # kısmında taşınır, sunucuya gitmez; 7 gün sonra açılmaz. Elle düzenlenir.

Metinler `src/legal.ts` içinden `npm run yasal-sayfalar` ile üretilir; elle düzenlemeyin.
