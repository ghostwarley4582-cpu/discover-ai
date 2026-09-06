# DISCOVER AI

Bütçe + zaman + mod üzerinden kişisel aktivite/deneyim önerileri sunan mobil uyumlu MVP.

## GitHub Pages
1. `index.html` dosyasını repoya yükle.
2. Settings → Pages → Deploy from branch → `main` / root seç.
3. Gerçek AI, auth, ödeme ve admin işlemleri için backend bağlanmalıdır.

## Güvenlik
Bu MVP'de gerçek secret/API key bulunmaz. Üretimde AI ve ödeme anahtarları frontend'e konulmamalı; server-side secret olarak tutulmalı, tüm admin işlemleri authorization + audit log ile korunmalıdır.
