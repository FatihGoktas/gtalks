# GTalks

GTalks, arkadaşlarınızla sesli ve görüntülü konuşma için bir uygulamadır.

Web adresi: https://gtalks.albatrosapps.workers.dev

## İndir

Son sürüm: **1.0.0**. Tüm sürümler: [sürüm sayfası](https://github.com/FatihGoktas/gtalks/releases).

- Windows: [GTalks-Kurulum.zip](https://github.com/FatihGoktas/gtalks/releases/latest/download/GTalks-Kurulum.zip)
- macOS: [GTalks-mac.dmg](https://github.com/FatihGoktas/gtalks/releases/latest/download/GTalks-mac.dmg)

### Windows

1. ZIP dosyasını indirin.
2. ZIP dosyasına sağ tıklayın ve "Tümünü ayıkla" seçin.
3. `GTalks-Kurulum.exe` dosyasını çalıştırın.
4. Windows SmartScreen uyarısı çıkarsa "Ek bilgi" seçin.
5. "Yine de çalıştır" seçin.

Uygulama henüz imzalı değildir. Bu nedenle uyarı çıkar.

### macOS

1. `GTalks-mac.dmg` dosyasını açın.
2. `GTalks` uygulamasını "Uygulamalar" klasörüne sürükleyin.

Uygulama Apple tarafından onaylıdır.

## Yenilikler (1.0.0)

- Oda mesajları: yazı, emoji ve resim paylaşın. Mesajlar 24 saat sonra silinir.
- @bahsetme, bildirim zili ve "Cevap yaz" ile alıntılı yanıt.
- Gürültü engelleme için iki model: Hafif (RNNoise) ve Güçlü (DeepFilterNet3).
- Otomatik ses dengeleme: yüksek ve kısık sesler sizin için eşitlenir.
- Odalar artık 20 kişilik.
- Yeni oda sayfası ve yeni ana sayfa.

## Dosyayı doğrula

Her sürümle birlikte `SHA256SUMS.txt` dosyası yayınlanır. İndirdiğiniz dosyanın özeti bu dosyadaki değerle aynı olmalıdır.

1. Windows için komut satırında şunu çalıştırın:

   ```
   certutil -hashfile GTalks-Kurulum.zip SHA256
   ```

2. macOS için terminalde şunu çalıştırın:

   ```
   shasum -a 256 GTalks-mac.dmg
   ```

3. Çıkan değeri `SHA256SUMS.txt` içindeki değerle karşılaştırın.

## Not

Bu depoda uygulamanın kaynak kodu yoktur. Bu depo yalnızca kurulum dosyalarını içerir.
