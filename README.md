# KAINAK

KAINAK'ın web sitesi: Şema Terapi kitapçığı, yin yoga grupları, online danışmanlık, yazılar ve podcast.

Site tek bir dosyadan oluşur: `index.html`. Renkler, yazı tipleri ve tüm stiller bu dosyanın en üstündeki `<style>` bölümündedir.

## Renkleri değiştirmek

`index.html` içinde `:root{` ile başlayan bloğu bul. Tüm renkler burada tanımlı:

| Değişken | Renk | Kullanım |
|---|---|---|
| `--bg` | `#E9E7DE` | Sayfa zemini (sıcak taş) |
| `--surface` | `#FAF9F4` | Kartlar, formlar |
| `--sea` | `#23586A` | Boğaz mavisi: butonlar, vurgular |
| `--fig` | `#4E6853` | Adaçayı yeşili: ikincil vurgular |
| `--dusk-1` / `--dusk-2` | `#173840` / `#285A60` | Giriş bölümündeki derin su |
| `--dusk-light` | `#E6C495` | Giriş bölümündeki akşam ışığı |
| `--foot` | `#1D4148` | Alt bilgi |

## Yayına almadan önce doldurulacaklar

- [ ] Kitapçık fiyatı (`₺ —` yazan yer)
- [ ] Shopier satın alma bağlantısı (`Shopier ile satın al` butonunun `href` değeri)
- [ ] Başvuru formunu bir e-posta servisine bağlamak (ör. Formspree)
- [ ] Podcast bağlantıları ve Spotify oynatıcısı
- [ ] Instagram, YouTube, Spotify, LinkedIn bağlantıları
- [ ] Yin yoga grup detayları (kişi sayısı, süre, yer)
- [ ] Blog yazıları (şu an "örnek" etiketli)
- [ ] Portre fotoğrafı ve Hakkımda metni

## Yayın

Site GitHub Pages ile yayınlanır: Settings → Pages → Branch: `main`, klasör: `/ (root)`.
