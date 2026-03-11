# Xtream Codes to M3U Converter
**Tarih:** 2026-03-11

## Özet
Xtream Codes API kimlik bilgilerini M3U/M3U8/JSON playlist dosyasına dönüştüren Node.js web uygulaması. Kullanıcılar IPTV sağlayıcı bilgilerini girerek kategori bazlı, özelleştirilebilir playlist indirebilir.

## Yapı
- Kök: `app.js` (ana uygulama, ~31KB), `package.json`, `docker-compose.yml`, `Dockerfile`
- Klasörler: `views/` (EJS şablonları), `screenshots/`

## Teknoloji
Node.js + Express, EJS, Bootstrap 5, Axios, Docker

## Özellikler
- Xtream Codes API entegrasyonu (Live TV + VOD)
- Çoklu export formatı: M3U, M3U8, JSON
- Kategori yönetimi: seçim, drag & drop sıralama, kalite filtresi (HD/FHD/4K)
- EPG & Catch-up desteği, çok dil (TR/EN/DE/FR), credential localStorage kayıt

## İstatistik
Dosya: ~8, Teknoloji: Node.js/Express
