
# Watch Collection – Yayınlama Rehberi

Bu klasör, GitHub Pages'te yayınlayabileceğin hazır bir başlangıç yapısıdır.

## 1) Dosya Yapısı
- index.html        → Ana sayfa
- watches.json      → Kartları besleyen veri dosyası
- images/           → Tüm saat fotoğrafların (buraya koy)

## 2) Fotoğrafları ekle
- Kendi fotoğraflarını `images/` klasörüne kopyala.
- İsimleri `watches.json` içindeki `img` değerleriyle aynı yap. Örn:
    images/perfex-chronograph.jpg
    images/seamaster-300-1.jpg
    ...
- İstersen `watches.json` dosyasındaki başlık, açıklama ve dosya adlarını da değiştirebilirsin.

## 3) Yerelde görüntüle (opsiyonel)
- index.html dosyasını tarayıcıda aç, fotoğrafların görünür olmalı.
  (Bazı tarayıcılarda JSON dosyasını dosya:// üzerinden okumaya izin verilmez.
   Bu durumda GitHub Pages'e yükledikten sonra kesin çalışır.)

## 4) GitHub'a yükle ve Pages'i aç
- GitHub'ta yeni bir public repo oluştur (ör. watch-collection).
- Bu klasörün içindekileri (index.html, watches.json, images/) repo'ya yükle.
- Repo → Settings → Pages → Deploy from a branch → Branch: main → /root
- 1-2 dakika sonra site şu şekilde açılır:
  https://<kullanici-adin>.github.io/<repo-adi>/

## 5) Özelleştirme
- `watches.json` içine yeni saatler ekle/çıkar.
- Tasarım için index.html'in `<style>` bölümünü düzenleyebilirsin.
- Filtre/arama istersen bana söyle, küçük bir JS ile ekleyeyim.
