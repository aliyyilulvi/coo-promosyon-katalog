# COO Promosyon — Ürün Kataloğu

2026 Promosyon Kataloğu'ndan otomatik oluşturulmuş, 310 ürünlük tek sayfa
katalog sitesi. Kategori filtresi ve canlı arama içerir.

🔗 **Canlı site:** Bu repo'da GitHub Pages aktif edildikten sonra
`https://KULLANICI_ADIN.github.io/REPO_ADI/` adresinden yayınlanır.

---

## Bu repoyu GitHub'da nasıl yayına alırsın (5 dakika, ücretsiz)

### 1) Yeni repo oluştur
- [github.com/new](https://github.com/new) adresine git
- Repository name: `coo-promosyon-katalog` (istediğin ismi verebilirsin)
- **Public** seç
- "Create repository" butonuna bas — README/gitignore ekleme, boş bırak

### 2) Dosyaları yükle
- Oluşan boş repo sayfasında **"uploading an existing file"** linkine tıkla
- Bu klasördeki **tüm dosya ve klasörleri** (index.html, assets/, .nojekyll,
  README.md, BENI-OKU.txt) sürükleyip bırak
- Alt kısımda "Commit changes" butonuna bas
  - Not: `assets/img` klasöründe 310 görsel var, tarayıcı üzerinden
    sürükle-bırak biraz zaman alabilir. Alternatif olarak Git kullanıyorsan
    aşağıdaki komutları kullanabilirsin:

```bash
cd github-repo
git init
git add .
git commit -m "İlk yükleme: COO Promosyon kataloğu"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADIN/REPO_ADI.git
git push -u origin main
```

### 3) GitHub Pages'i aktif et
- Repo sayfasında **Settings** sekmesine git
- Sol menüden **Pages**'i seç
- "Build and deployment" altında **Source: Deploy from a branch** seç
- **Branch: main**, klasör: **/ (root)** seç → **Save**
- 1-2 dakika içinde sayfanın üstünde yeşil bir kutu içinde canlı linkin
  görünecek: `https://KULLANICI_ADIN.github.io/REPO_ADI/`

Bu kadar — tamamen ücretsiz ve kalıcı bir link elde etmiş olursun.

---

## Dosya yapısı

```
index.html          → Site (tüm HTML/CSS/JS tek dosyada)
assets/img/          → 310 ürün görseli (JPG)
assets/products.json → Ürün verisi (yedek/referans)
assets/favicon.svg   → Logo / sekme ikonu
.nojekyll            → GitHub Pages'in klasörleri olduğu gibi sunması için
```

## Siteyi güncellemek istersen

`index.html` içindeki metinleri (iletişim bilgileri, başlıklar) veya
`<style>` bloğundaki renk kodlarını (`--emerald-...`, `--gold-...`)
düzenleyip GitHub üzerinden dosyayı tekrar yükleyebilir ya da `git push`
ile güncelleyebilirsin. Değişiklik birkaç saniye içinde canlı sitede
görünür.
