# Bölüm Defteri — Kurulum Rehberi (Android)

Uygulama tamamen ücretsiz çalışır: sunucusu yoktur, verilerin telefonunda saklanır.
Kurulum iki aşamadır: (1) dosyaları ücretsiz bir adrese yükle, (2) telefonuna kur.

## 1. Aşama — GitHub Pages'e yükleme (bir kere, ~5 dakika)

1. github.com adresinde ücretsiz bir hesap aç (varsa giriş yap).
2. Sağ üstteki **+** işaretine bas → **New repository**.
3. Repository name kısmına `bolum-defteri` yaz, **Public** seçili kalsın → **Create repository**.
4. Açılan sayfada **uploading an existing file** bağlantısına tıkla.
5. Bu klasördeki 5 dosyayı sürükleyip bırak:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`
   → altta **Commit changes** butonuna bas.
6. Üst menüden **Settings** → sol menüden **Pages** bölümüne gir.
7. "Branch" altında **main** seç, klasör **/ (root)** kalsın → **Save**.
8. 1-2 dakika sonra aynı sayfada adresin görünür:
   `https://KULLANICIADIN.github.io/bolum-defteri/`

## 2. Aşama — Telefona kurma

1. Android telefonunda **Chrome** ile yukarıdaki adresi aç.
2. Sağ üstteki **⋮** menüsüne bas → **Ana ekrana ekle** (veya "Uygulamayı yükle") → **Yükle**.
3. Artık ana ekranında ikonuyla duran, tam ekran açılan bir uygulaman var.

## Önemli notlar

- **Verilerin telefonunda saklanır.** Uygulama içindeki ⇩ (Yedek al) butonuyla
  arada bir yedek indir; telefon değiştirirsen ⇧ (Yedek yükle) ile geri getirirsin.
- Chrome'da "site verilerini sil / tarama verilerini temizle" yaparsan kayıtlar
  silinebilir — yedeğin varsa sorun olmaz.
- Dizi ve anime bilgileri TVmaze'den, filmler iTunes arşivinden gelir;
  ikisi de ücretsizdir, hesap veya anahtar gerektirmez.
- İleride uygulamada değişiklik yaparsak, sadece yeni `index.html` dosyasını
  GitHub'da aynı isimle tekrar yüklemen yeterli.
