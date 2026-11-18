# Minimal Kampanya Demo Görevleri

- [x] **1. Hugo İskeleti:** `hugo.toml`, `layouts/index.html` ve `layouts/_default/single.html` dosyalarını oluştur.
- [x] **2. Örnek İçerikler:** `content/_index.md` (anasayfa) ve `content/duyurular/ilk-duyuru.md` (1 adet içerik) oluştur.
- [x] **3. CMS Bağlantı Dosyası:** Kök dizine `.pages.yml` ekle (anasayfa metni ve duyurular koleksiyonunu tanımla).
- [x] **4. Yerel Test:** Terminalde `hugo server` çalıştırıp `localhost:1313` üzerinde anasayfa ve duyuru linkini doğrula.
- [ ] **5. GitHub & Yayın:** Projeyi yeni bir GitHub reposuna gönder (push).
- [ ] **6. UI Panel Testi:** `app.pagescms.org` adresine GitHub ile giriş yap, repoyu seç, arayüzden yeni bir duyuru ekleyip "Save/Publish" butonuna bas ve GitHub'a otomatik commit düştüğünü gör.
- [ ] **7. Canlı Yayın (Cloudflare Pages):** Cloudflare Pages üzerinden repoyu bağla (Build command: `hugo`, Output directory: `public`) ve `.pages.dev` adresinden canlı siteyi kontrol et.