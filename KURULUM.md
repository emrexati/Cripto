# Marjin Sinyal — iPhone kurulumu

Uygulama 4 dosyadan oluşur: index.html, manifest.webmanifest, icon-180.png, icon-512.png.
Bunları ücretsiz bir HTTPS adresine koyup Safari'den "Ana Ekrana Ekle" yapacaksınız.

## 1) GitHub Pages'e yükleme (ücretsiz, kalıcı — iPhone'dan da yapılabilir)
1. github.com'da ücretsiz hesap açın / giriş yapın.
2. Sağ üst "+" → New repository. Ad örneği: `ms-panel` (tahmin edilmesi zor bir ad seçin). Public seçin, Create.
3. "uploading an existing file" bağlantısına dokunun → zip'ten çıkan 4 dosyayı seçin → Commit changes.
4. Repo → Settings → Pages → Branch: `main`, klasör `/ (root)` → Save.
5. 1-2 dakika sonra adres: `https://KULLANICIADINIZ.github.io/ms-panel/`

Not: Ücretsiz GitHub Pages herkese açıktır ama adresi bilmeyen bulamaz; sayfa arama motorlarına kapalıdır (noindex).
Uygulama hiçbir kişisel veri, API anahtarı veya bakiye bilgisi göndermez; ayarlar sadece telefonunuzda saklanır.

## 2) iPhone'a ekleme
1. Adresi **Safari**'de açın.
2. Paylaş düğmesi (□↑) → **Ana Ekrana Ekle** → "Web Uygulaması olarak aç" açık kalsın → Ekle.
3. Ana ekrandaki "Marjin Sinyal" ikonundan açın: tam ekran, uygulama gibi çalışır.

## Bilinmesi gerekenler
- Veriler Binance WebSocket API'sinden canlı çekilir; internet gerekir.
- Otomatik yenileme yalnızca uygulama açıkken çalışır. Uygulamaya geri döndüğünüzde veri 2 dakikadan eskiyse kendiliğinden yenilenir.
- iPhone'da titreşim yok; yeni sinyalde ekranın üstünde sarı uyarı çıkar.
- Yatırım tavsiyesi değildir. Kaldıraçlı işlemde bakiyenin tamamı kaybedilebilir.
