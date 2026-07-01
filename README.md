# 🎬 Video Oynatıcı Pro - Güvenlikle Tasarlanmış

> **Şifreli, Gizli ve Tam Kontrolde Olan Video Oynatıcı**

![Security](https://img.shields.io/badge/Security-AES--256-brightgreen)
![Privacy](https://img.shields.io/badge/Privacy-No%20Telemetry-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Android](https://img.shields.io/badge/Android-5.0+-orange)

---

## 🌟 Özellikler

### 🎮 Oynatıcı Özellikleri
- ▶️ **Video Oynatma** - MP4, WebM, Ogg formatları
- ⏪ **10 Saniye Geri** - Hızlı ilgili bölüme gitme
- ⏭️ **10 Saniye İleri** - Hızlı ileri sarma
- 🎨 **Canlı Görüntü Iyileştirme**
  - Parlaklık (50%-150%)
  - Kontrast (50%-150%)
  - Doygunluk (50%-150%)
- 🔊 **Ses Iyileştirme**
  - Bass Boost (0%-100%)
  - Treble Boost (0%-100%)
- ⬇️ **Video İndirme** - İlerleme göstergesi ile
- ⛶ **Tam Ekran** - Mobil uyumlu
- 🔊 **Ses Kontrol** - Sessize alma, seviye ayarı

### 🔒 Güvenlik Özellikleri
- 🔐 **AES-256 Şifreleme** - Tüm veriler kodlandı
- 📱 **Lokal Depolama** - Hiçbir veri sunucuya gönderilmez
- ❌ **Telemetri Yok** - Sizi izlemeyiz
- 🚫 **Reklam Yok** - Hiçbir reklam
- 🔗 **Üçüncü Parti Yok** - Sadece gerekli açık kaynak kütüphaneler
- 📴 **Çevrimdışı Çalışır** - İnternet olmadan da oynatıcı açılır
- ✅ **Açık Kaynak** - Kodu denetleyebilirsin
- 📋 **Minimal İzinler** - Yalnızca gerekli izinler

---

## 📁 Proje Yapısı

```
video-player-pro/
│
├── 📄 VideoPlayerApp.tsx          # Ana Uygulama Bileşeni
├── 🔐 SecurityService.ts          # Güvenlik & Şifreleme
├── 📋 capacitor.config.json       # Capacitor Ayarları
├── 🔧 vite.config.ts              # Vite Build Config
├── 🎨 tailwind.config.js          # Tailwind CSS Config
├── ⚙️ tsconfig.json               # TypeScript Config
├── 📦 package.json                # Bağımlılıklar
├── 📱 AndroidManifest.xml         # Android İzinler
│
├── 📚 Dokümantasyon/
│   ├── APK_BUILD_GUIDE.md         # Detaylı APK Oluşturma
│   ├── QUICK_START.md             # 5 Dakikada Başlangıç
│   ├── PRIVACY_SECURITY.md        # Güvenlik Detayları
│   └── README.md                  # Bu dosya
│
└── 🤖 android/                    # Android Projesi (otomatik oluşturulur)
```

---

## 🚀 Kurulum & Başlangıç

### Hızlı Kurulum (5 dakika)

1. **Ön koşulları yükle:**
   - Java Development Kit (JDK 17+)
   - Node.js 16+
   - Android SDK (Android Studio)

2. **Projeyi kurulum yaparken:** 
   ```bash
   npm install
   ```

3. **APK oluştur:**
   ```bash
   npm run build
   npx cap add android
   npx cap copy
   npx cap open android
   ```

4. **Android Studio'da derleme yaparak APK oluştur**

📖 **Detaylı rehber:** [APK_BUILD_GUIDE.md](./APK_BUILD_GUIDE.md)

---

## 🔐 Güvenlik Garantileri

### Veri Güvenliği
- ✅ **AES-256 Şifreleme** - Endüstri standardı
- ✅ **Lokal Depolama** - Veriler cihazda kalır
- ✅ **Hiçbir Senkronizasyon** - Buluta yüklenmez
- ✅ **Silme Hakkı** - İstediğinde sil

### Gizlilik
- ✅ **Telemetri Yok** - Sizi izlenmez
- ✅ **Analytics Yok** - Oturum takibi yok
- ✅ **Reklam Yok** - Reklam SDK'sı yok
- ✅ **Trackers Yok** - Hırsız izleri yok

### Açıklık
- ✅ **Açık Kaynak** - Kod herkese açık
- ✅ **Denetlenebilir** - Güvenlik poliçemizi kontrol et
- ✅ **Minimal İzinler** - Yalnızca gerekli izinler
- ✅ **Şeffaf Yapı** - Ne yapıyor görebilirsin

📖 **Detaylı güvenlik politikası:** [PRIVACY_SECURITY.md](./PRIVACY_SECURITY.md)

---

## 💻 Teknoloji Stack

| Teknoloji | Versiyon | Amaç |
|-----------|----------|------|
| **React** | 18.2+ | UI Framework |
| **TypeScript** | 5.0+ | Tipe göre kontrol |
| **Capacitor** | Latest | Native Mobile App |
| **Tailwind CSS** | 3.3+ | Styling |
| **Vite** | 4.3+ | Build Tool |
| **Lucide React** | Latest | İkonlar |
| **Web Audio API** | HTML5 | Ses işlemler |

---

## 🎯 Sistem Gereksinimleri

### Geliştirme Ortamı
- **OS:** Windows 10+, macOS 11+, Linux
- **Node.js:** 16+
- **Java:** JDK 17+
- **Android SDK:** API 21 (5.0) - API 34 (14)
- **Disk:** 2 GB boş alan
- **RAM:** 4 GB minimum

### Çalışma Ortamı (Cihazda)
- **Android:** 5.0+ (API 21+)
- **RAM:** 512 MB
- **Depolama:** 20 MB
- **İnternet:** İsteğe bağlı (video indirmek için)

---

## 📊 Özellikleri Detaylı

### Video Oynatıcı
```
┌─────────────────────────────┐
│  Video Player              │
│ ◀────────────●────────────▶ │
│  [Kontrol Butonları]       │
│ ▶ ⏪ ⏭ 🔄 ⬇ ⚙ 🔊 ⛶       │
└─────────────────────────────┘
```

**Desteklenen Formatlar:**
- MP4 (H.264/H.265)
- WebM (VP8/VP9)
- Ogg (Theora)
- HDR 10+ (varsa)
- Dolby Digital (varsa)

### Görüntü İyileştirme
```
Orijinal     →  Parlaklık  →  Kontrast  →  Doygunluk
Video         (50%-150%)      (50%-150%)    (50%-150%)
              ├─ Koyu      ├─ Düşük      ├─ Soluk
              ├─ Normal    ├─ Normal     ├─ Normal
              └─ Parlak    └─ Yüksek     └─ Canlı
```

### Ses İyileştirme
```
Giriş Ses   →  Bass Boost  →  Treble Boost  →  Çıkış
            (50%-200%)        (50%-200%)
            ├─ İnce       ├─ Düşük
            ├─ Normal     ├─ Normal
            └─ Ağır       └─ Yüksek
```

---

## 🔧 Geliştirme

### Lokal Ortamda Geliştirme
```bash
# Bağımlılıkları yükle
npm install

# Dev sunucusu başlat
npm run dev

# Tarayıcıda localhost:3000 açılır
```

### Build
```bash
# Production build
npm run build

# Dist klasörü oluşturulur
ls dist/
```

### Capacitor Senkronizasyonu
```bash
# Değişiklikleri Android'e kopyala
npx cap copy

# Veya sync (clean sync)
npx cap sync
```

---

## 📱 Play Store'a Yayınlama (İsteğe Bağlı)

1. **APK/AAB Oluştur** (Release yapısında)
2. **Google Play Console'da** uygulama oluştur
3. **APK/AAB Yükle**
4. **Açıklamalar ve Ekran Görüntüleri** ekle
5. **Test Yayını Yap** (beta)
6. **Yayınla** (production)

---

## 📋 Yapılacaklar (Gelecek Sürümler)

- [ ] Playlist desteği
- [ ] Başlangıç/Bitiş zamanı belirleme
- [ ] Altyazı desteği (SRT, VTT)
- [ ] Subtitle kaydı
- [ ] Video filtreleri (ekvalize, efekt)
- [ ] Cihazlar arasında senkronizasyon
- [ ] Premium özellikleri (isteğe bağlı)
- [ ] Dark/Light tema
- [ ] Yardım ekranları

---

## 🐛 Sorun Bildirme

Eğer bug bulursan:

1. [Issues](https://github.com/your-repo/issues) sekmesine git
2. "New Issue" butonuna tıkla
3. Detaylı açıklama yaz:
   - Ne yapmaya çalıştığın
   - Ne olması gerektiği
   - Ne oldu (hata)
   - Ekran görüntüsü (varsa)
4. Gönder!

---

## 🔒 Güvenlik Raporu

Eğer güvenlik açığı bulursan:
- **HIÇBIR ZAMAN** herkese açık olarak rapor etme
- **Özel olarak** bildikişilere gönder
- **72 saat bekle** yanıt için
- **Uygulanmış fix'i duyur** güvenlik güncelleme ile

---

## 📄 Lisans

MIT Lisansı - Kodu liberce kullanabilir, değiştirebilir ve dağıtabilirsin.
Sadece orijinal lisans sahibi olarak beni belirt.

```
Copyright (c) 2024 Video Player Pro

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

---

## 👥 Katkıda Bulunma

Katkıları kabul ediyorum! Lütfen:

1. Fork et
2. Branch oluştur (`git checkout -b feature/AmazingFeature`)
3. Commit et (`git commit -m 'Add AmazingFeature'`)
4. Push et (`git push origin feature/AmazingFeature`)
5. Pull Request aç

---

## 🤝 İletişim

- 📧 Email: [email@example.com]
- 🐙 GitHub: [github.com/username]
- 🐦 Twitter: [@username]

---

## 🙏 Teşekkürler

- React & React Native Community
- Capacitor Team
- Tailwind CSS Ekibi
- Android Güvenlik Ekibi

---

## ⭐ Yıldız Ver!

Bu proje sana yardımcı olduysa, lütfen yıldız ver! ⭐

---

**Son Güncelleme:** Aralık 2024  
**Versiyon:** 1.0.0  
**Durum:** ✅ Stabil  

---

**Güvenlikle İzle, Gizlikle Oyna! 🎬🔒**
