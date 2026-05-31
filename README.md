# Elyrion'a Hoş Geldin — Oyuncu Hazırlık Rehberi

**Karanlık Doğuş'un Yankıları** · D&D 5e kampanyası için oyunculara yönelik, **spoiler içermeyen** sinematik tanıtım sitesi.

Çok sayfalı, "eski kitap" temalı bir statik site: atmosferik bir kapak, bölüm bölüm sayfalar, kaydırınca beliren içerikler ve sayfa-çevirme navigasyonu. Görseller *Karanlık Hasar* kitabından alınmıştır.

---

## 🌐 GitHub Pages'te Yayınlama (adım adım)

1. GitHub'da **yeni bir repo** oluştur (örn. `elyrion-rehberi`). **Public** olmalı (ücretsiz Pages için).
2. Bu klasörün **içindeki tüm dosyaları** (klasörün kendisini değil) repo'ya yükle:
   `index.html`, diğer `.html` dosyaları, `assets/` klasörü, `.nojekyll`, `README.md`.
   - Web'den: repo sayfasında **Add file → Upload files**, hepsini sürükle-bırak, **Commit**.
   - Ya da `git` ile: bu klasörün içinde `git init`, `git add .`, `git commit`, `git push`.
3. Repo'da **Settings → Pages**'e gir.
4. **Source**: `Deploy from a branch` → **Branch**: `main` → klasör `/ (root)` → **Save**.
5. 1–2 dakika sonra siten şurada yayında olur:
   `https://KULLANICIADIN.github.io/REPO-ADI/`

> **Önemli:** `index.html` ve `.nojekyll` dosyaları repo'nun **kök dizininde** olmalı. Tüm bağlantılar görecelidir, bu yüzden site proje alt-yolunda (`/REPO-ADI/`) sorunsuz çalışır.

---

## 📖 İçindekiler

| Sayfa | Bölüm |
|---|---|
| `index.html` | Kapak |
| `dunya.html` | I. Elyrion |
| `karanlik-dogus.html` | II. Karanlık Doğuş |
| `simdi.html` | III. Şu An: 1492 |
| `curume.html` | IV. Çürüme |
| `uluslar.html` | V. On İki Ulus |
| `tanrilar.html` | VI. Tanrılar & Kadim Varlıklar |
| `irklar.html` | VII. Halklar & Irklar |
| `karakter.html` | VIII. Karakterini Yarat |
| `assets/` | görseller, stil (`css`), betik (`js`) |

## 🧩 Yapı
```
.
├── index.html              # kapak
├── *.html                  # bölüm sayfaları
├── .nojekyll               # GitHub Pages: Jekyll'i devre dışı bırakır
├── assets/
│   ├── css/style.css
│   ├── js/site.js
│   └── img/                # kitaptan görseller
└── README.md
```

## 🔒 Spoiler notu
Bu rehber **yalnızca karakterlerin de bileceği** genel bilgileri içerir. Kampanyanın gizli gerçekleri DM'dedir; bu sayfalarda yer almaz.

## ✒️ Künye
Elyrion evreni ve görseller: **Mevlüt Furkan İnce — _Karanlık Hasar_**.
Görseller yalnızca bu kampanyanın tanıtımı için kullanılmıştır.
