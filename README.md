# Hesap Defteri — FINAL

Bu sürüm, GitHub Pages üzerinde çalışacak şekilde hazırlanmıştır. GitHub Pages statik HTML/CSS/JS dosyalarını doğrudan yayınlayabilir. `.nojekyll` dosyası da eklenmiştir.

## İçerik
- Gelir/gider: tarih, kategori, açıklama, ödeme yöntemi, TRY/EUR/USD.
- Aylık özet, önceki/sonraki ay, aylık net, geçmiş aylardan devir.
- Kategori dağılımı ve aylık gider grafiği.
- Aylık bütçe limitleri.
- Otomatik tekrarlayan giderler.
- Düzenleme/silme.
- JSON backup/restore.
- IndexedDB.
- BIST hisse/fon ve yabancı hisse için lot/adet bazlı alış, çoklu alış, ortalama maliyet, satış, gerçekleşen K/Z, temettü.
- Portföy dağılımı.
- Bileşik getiri: aylık katkı veya tek seferlik yatırım.
- Birikim hedefleri.
- Döviz: Frankfurter v2 + TCMB önceliği; cache/fallback.
- Altın: Harem canlı sayfa okuyucu + spot fallback.
- Hisse fiyatı: yapılandırılabilir proxy veya Yahoo chart public endpoint; başarısızsa uygulama çökmez.

## Kurulum
Yeni boş GitHub repository → bu ZIP'in içindeki dosyaların tamamını root'a yükle → Settings → Pages → Deploy from branch → main / root.

GitHub Pages için `index.html` yayın kaynağının kökünde bulunmalıdır.

## Önemli piyasa verisi notu
BIST resmi gerçek zamanlı veri lisanslıdır; ücretsiz/public kaynaklar gecikmeli veya zaman zaman erişilemez olabilir. Uygulama son bilinen fiyatı saklayarak portföy hesabını bozmadan çalışmaya devam eder.

Harem fiziksel alış/satış fiyatı ile spot altın fiyatı aynı değildir. Harem okuyucu çalışmazsa spot fallback kullanılır ve kaynak ekranda belirtilir.

Kişisel finans kayıtları GitHub'a yüklenmez; cihazdaki IndexedDB'de tutulur. JSON yedeklerini güvenli yerde saklayın.
