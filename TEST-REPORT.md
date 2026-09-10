# Hesap Defteri — UI Revizyon Kontrol Raporu

## UI/UX
- iOS safe-area üst boşluğu: düzeltildi.
- iOS safe-area alt boşluğu / Home Indicator: düzeltildi.
- Alt navigasyon: sabit, 4 sekmeli ve mobil odaklı.
- Koyu yeşil hero alanı: referans tasarıma göre yenilendi.
- Krem arka plan, kırık beyaz kartlar ve düşük kontrastlı border sistemi: yenilendi.
- Gider/negatif renkleri: soft rust.
- Gelir/pozitif renkleri: soft green.
- Tipografi: Fraunces + Inter korunuyor.
- Form elemanları ve butonlar: daha soft, geniş dokunma alanlı ve tutarlı hale getirildi.
- Modal: iPhone ekranına uygun bottom-sheet görünümüne getirildi.

## Grafikler
- Kategori dağılımı donut grafiği korunuyor.
- Aylık trend artık hem gelir hem gideri ayrı barlarla gösteriyor.
- Portföy/varlık dağılımı donut grafiği korunuyor.
- Birikim hedeflerinde ilerleme barı korunuyor.

## Teknik kontroller
- app.js: `node --check` PASS
- market-data.js: `node --check` PASS
- service-worker.js: `node --check` PASS
- manifest.json: JSON parse PASS
- GitHub Pages statik dosya yapısı: PASS
