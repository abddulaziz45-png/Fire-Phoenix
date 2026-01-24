# ✅ GitHub'a Yüklenmesi Gereken Dosyalar Kontrol Listesi

## 📁 docs/ Klasörü Yapısı

GitHub'a yüklerken `docs` klasörünün içindeki TÜM dosya ve klasörleri yüklemelisiniz:

```
docs/
├── index.html          ✅ MUTLAKA
├── README.md           ✅
├── audio/              ✅ Tüm klasör
│   ├── voices-of-fire-en.mp3
│   ├── voices-of-fire-it.mp3
│   ├── voices-of-fire-ru.mp3
│   └── voices-of-fire-tr.mp3
├── images/             ✅ Tüm klasör (1224 (3).mp4 hariç)
│   ├── background.jpg
│   ├── building-burning.png
│   ├── chicago fire/
│   ├── game/
│   ├── before after/
│   └── ... (tüm diğer dosyalar)
└── videos/             ✅ Tüm klasör (chicago 1871.mp4 hariç)
    ├── timeline-animation.mp4
    ├── places/
    ├── moscow-fire/
    └── ... (tüm diğer dosyalar)
```

## ⚠️ Yüklenmeyecek Dosyalar

- ❌ `images/1224 (3).mp4` (173 MB - çok büyük, kullanılmıyor)
- ❌ `videos/chicago 1871.mp4` (172 MB - çok büyük, YouTube'dan geliyor)

## 🔍 Sorun Giderme

### Fotoğraflar görünmüyorsa:

1. **Browser Console'u açın** (F12 → Console)
2. **Hataları kontrol edin** - hangi dosyalar bulunamıyor?
3. **GitHub repository'nizde kontrol edin:**
   - `docs/images/` klasörü var mı?
   - İçindeki dosyalar yüklü mü?

### Animasyonlar çalışmıyorsa:

1. **Videos klasörünü kontrol edin:**
   - `docs/videos/timeline-animation.mp4` var mı?
   - `docs/videos/places/` klasörü var mı?
   - `docs/videos/moscow-fire/` klasörü var mı?

### Dosya Yolları Kontrolü:

Tüm dosya yolları göreli olmalı:
- ✅ `images/...` (doğru)
- ✅ `videos/...` (doğru)
- ✅ `audio/...` (doğru)
- ❌ `/images/...` (yanlış - başında / olmamalı)
- ❌ `../images/...` (yanlış)

## 🚀 Hızlı Çözüm

Eğer hala sorun varsa:

1. GitHub repository'nizde `docs` klasörüne gidin
2. Tüm alt klasörleri kontrol edin
3. Eksik dosyaları tekrar yükleyin
4. Browser cache'ini temizleyin (Ctrl+F5)







