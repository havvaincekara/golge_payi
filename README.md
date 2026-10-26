# Negatif

Kendisine bakıldıkça kaybolan, kendisinden uzaklaşıldıkça görünür olan bir ekran.
Yüksek lisans bitirme projesi · Grafik tasarım · 2026

## Sayfalar

| Dosya | İçerik |
| --- | --- |
| `index.html` | Proje sunum sayfası |
| `tipografi.html` | 01 · Metin: uzaktan okunan, yaklaştıkça çözülen cümle (kamerasız da çalışır) |
| `puruzsuz.html` | 02 · Pürüzsüz: maruziyet arttıkça maskeye dönüşen yüz (kamera gerekir) |
| `kirpma.html` | 03 · Göz Kapağı: yalnızca göz kırpma anlarında oluşan portre (kamera gerekir) |

`kirpma.html#koridor` ve `kirpma.html#iceri` adresleri, sergide iki ayrı ekran için tek görünümü açar.

## GitHub Pages'te yayınlama

1. GitHub'da yeni bir depo aç (ör. `negatif`), görünürlüğü **Public** olsun.
2. **Add file → Upload files** ile bu klasördeki bütün dosyaları depo köküne yükle ve **Commit changes** de.
3. **Settings → Pages** bölümünde *Source* olarak **Deploy from a branch**, dal olarak **main** ve klasör olarak **/ (root)** seç, **Save** de.
4. Bir iki dakika sonra site `https://KULLANICI-ADIN.github.io/negatif/` adresinde açılır.

Kamera yalnızca https adreslerinde çalışır; GitHub Pages bunu kendiliğinden sağlar.

## Teknik not

Yüz tespiti için MediaPipe Face Landmarker (tasks-vision 0.10.14) tarayıcıda çalışır. Görüntü cihazdan çıkmaz ve kaydedilmez.
Ekrandaki cümle bir yer tutucudur; Byung-Chul Han'dan sayfa numarasıyla doğrulanmış bir alıntıyla değiştirilmelidir (`tipografi.html` → Ayarlar → Metin, kalıcı değişiklik için dosyadaki `text-input` alanı).
