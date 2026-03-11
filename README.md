# 🚀 Alperi Kelime Arama & Düzenleme Pro (V.5.0.0)

<div align="center">

![Version](https://img.shields.io/badge/Sürüm-V.5.0.0-brightgreen?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/Lisans-Sosyal%20Sorumluluk-red?style=for-the-badge&logo=heart)
![Status](https://img.shields.io/badge/Durum-Aktif-success?style=for-the-badge)

</div>

---

**Teknolojinin İyilikle Buluştuğu Nokta**

Alperi Kelime Arama & Düzenleme Pro, karmaşık kod dosyalarından gelişmiş belgelere kadar binlerce satır veri içinde ışık hızında arama yapmanızı ve sonuçları anında düzenlemenizi sağlayan profesyonel bir Windows aracıdır.

Ancak bu yazılımın asıl gücü kodlarda değil, temsil ettiği umutta gizlidir. Bu proje, **DMD (Duchenne Musküler Distrofi)** hastası **Toprak Kaan Selvi**'nin dünyanın en pahalı gen tedavisine ulaşabilmesi için bir **sosyal sorumluluk projesi** olarak geliştirilmiştir.

---

## 🆕 V.5.0.0 — Yenilikler

> Bu sürüm, kullanıcı geri bildirimlerine dayanarak hazırlanan en kapsamlı güncellememizdir.

| # | Yenilik | Açıklama |
|---|---------|----------|
| 1 | 🔤 **Büyük/Küçük Harf Duyarlı** | Tam eşleşme araması için checkbox ile açılır |
| 2 | 🧩 **Regex Modu** | `^hata.*kritik`, `\d{3}-\d{4}` gibi gelişmiş kalıplar |
| 3 | 🔗 **AND / OR Çoklu Kelime** | `hata VE kritik` veya `hata VEYA uyarı` |
| 4 | 🕘 **Arama Geçmişi** | Son 20 arama kaydedilir, tek tıkla geri yüklenir |
| 5 | 📤 **Dışa Aktarma** | Sonuçları Excel (.xlsx), CSV veya TXT olarak kaydet |
| 6 | 🎨 **Tema Seçici** | Koyu / Açık / Sistem teması — anında geçiş |

### Diğer İyileştirmeler
- ✅ Program açıldığında **"Nasıl Kullanılır?"** rehberi otomatik gösterilir
- ✅ Sonuç alanına **kaydırma çubuğu** eklendi
- ✅ Sağ tık menüsü için kullanıcı **yönlendirme mesajı** eklendi
- ✅ **"ARANIYOR..."** yazısı artık düzgün beyaz renkte görünüyor
- ✅ Editörde renklendirme **kapatıldığında** tag'ler anında temizleniyor
- ✅ Büyük dosyalarda (>1000 satır) renklendirme **otomatik kapanıyor**
- ✅ Kaydırma sırasında renklendirme **duraklatılıyor** — akıcı deneyim
- ✅ PDF sonuçları lisanssız kullanıcılara **tamamen gizleniyor**, sayıya dahil ediliyor
- ✅ **Özellikler & Sürüm Karşılaştırması** penceresi eklendi (Yardım menüsü)

---

## ✨ Tüm Özellikler

### 🟢 Ücretsiz Sürüm

| Özellik | Durum |
|---------|-------|
| Metin dosyalarında arama (.txt, .js, .php, .css, .py, .html vb.) | ✅ |
| Alt klasörler dahil recursive tarama | ✅ |
| Dosya isimlerinde arama | ✅ |
| Çoklu format filtreleme | ✅ |
| AND / OR çoklu kelime arama mantığı | ✅ |
| Regex (düzenli ifade) modu | ✅ |
| Büyük/küçük harf duyarlı arama | ✅ |
| Arama geçmişi (son 20) | ✅ |
| Tema seçici (Koyu / Açık / Sistem) | ✅ |
| Sonuçları dışa aktar (Excel, CSV, TXT) | ✅ |
| Klasör sürükle & bırak | ✅ |
| Aramayı durdurma | ✅ |
| Gösterilen sonuç limiti | İlk 3 |

### 💎 Full Sürüm (Bağışçılar İçin)

| Özellik | Durum |
|---------|-------|
| **PDF dosyalarının içeriğinde arama** | 💎 |
| **PDF sayfa & satır detayları** | 💎 |
| **Word (.docx) paragraf detayları** | 💎 |
| **Limitsiz sonuç görüntüleme** | 💎 |
| **Dahili Metin Editörü** | 💎 |
| **Syntax Highlighting** (PHP, JS, CSS, Python, HTML...) | 💎 |
| **Satır numarası gösterimi** | 💎 |
| **Bul & Değiştir** (Ctrl+H) | 💎 |
| **Satıra Git** (Ctrl+G) | 💎 |
| **Sağ tık → Editörde Düzenle** | 💎 |

---

## 📖 Kullanım

### Temel Arama
1. **Arama Terimi** kutusuna aramak istediğiniz kelimeyi yazın
2. **Klasör Yolu** kutusuna taranacak klasörü yazın ya da sürükleyin
3. Format seçin (isteğe bağlı)
4. **🚀 ARAMAYI BAŞLAT** butonuna tıklayın

### Yeni: Çoklu Kelime (AND / OR)
```
# Her iki kelime de bulunmalı (VE)
hata VE kritik

# En az biri yeterli (VEYA)
hata VEYA uyarı
```

### Yeni: Regex Modu
```regex
^hata          # Satır başında "hata"
\.php$         # ".php" ile biten satırlar
hata.*kritik   # "hata" ile başlayıp "kritik" geçen
\d{3}-\d{4}    # 555-1234 gibi telefon formatı
```

### Sonuçlarla Yapabilecekleriniz
> **Herhangi bir dosya ismine sağ tıklayın** → açılan menüden:
> - 📂 **Klasörü Aç** — Dosyanın bulunduğu klasörü açar
> - 📝 **Editörde Düzenle** — Dahili editörde açar *(Full Sürüm)*

---

## ❤️ Full Sürüm (Lisans) Nasıl Alınır?

Alperi Search Pro'nun Full Sürümüne sahip olmak aynı zamanda bir kahraman olmak demektir!

1. Aşağıdaki **T.C. Valilik İzinli** yardım hesaplarına en az **400 TL** bağış yapın
2. Bağış dekontunuzu **alper.peri@gmail.com** adresine gönderin
3. E-postanıza programda görünen **Cihaz Kodunu** ekleyin
4. Full Sürüm lisans anahtarınız e-posta adresinize iletilecektir

---

## 🏛️ Resmi Kampanya Bilgileri

| Bilgi | Detay |
|-------|-------|
| **Kampanya Sahibi** | YASİN ALPARSLAN SELVİ |
| **Faaliyet No** | `34.2024.2335` *(E-Devlet'ten sorgulanabilir)* |
| **Web Sitesi** | [toprakkaanselvi.org.tr](https://toprakkaanselvi.org.tr) |

### 🏦 Banka Hesapları

| Para Birimi | IBAN |
|-------------|------|
| 🇹🇷 **TL** | `TR60 0001 2001 2850 0001 1255 54` |
| 🇺🇸 **USD** | `TR18 0001 2001 2850 0023 0023 32` |
| 🇪🇺 **EUR** | `TR02 0001 2001 2850 0035 0016 17` |

---

## 📥 İndirme ve Kurulum

En güncel sürümü (V.5.0.0) doğrudan SourceForge üzerinden güvenle indirebilirsiniz:

👉 **[Alperi Search Pro İndir (SourceForge)](https://sourceforge.net/projects/alperi/files/Alperi_Kelime_Arama_Pro_Kurulum.exe/download)**

### Sistem Gereksinimleri
- Windows 10 / 11 (64-bit)
- 50 MB disk alanı
- İnternet bağlantısı gerekmez

---

## 📋 Sürüm Geçmişi

| Sürüm | Tarih | Öne Çıkan |
|-------|-------|-----------|
| **V.5.0.0** | Mart 2026 | Regex, AND/OR, geçmiş, dışa aktarma, tema seçici |
| V.4.0.1 | Mart 2026 | ARANIYOR yazısı düzeltmesi, hoşgeldin ekranı |
| V.4.0.0 | Mart 2026 | Dosya adı araması, 2 bölümlü sonuç ekranı, gelişmiş editör |

---

**Geliştirici:** Alper Peri | [alperperi.com](https://alperperi.com)

---
---

# 🚀 Alperi Search & Edit Pro (V.5.0.0)

<div align="center">

![Version](https://img.shields.io/badge/Version-V.5.0.0-brightgreen?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows)
![License](https://img.shields.io/badge/License-Social%20Responsibility-red?style=for-the-badge&logo=heart)

</div>

---

**Where Technology Meets Kindness**

Alperi Search & Edit Pro is a professional Windows tool that allows you to search through thousands of lines of data at lightning speed—from complex code files to advanced documents—and edit the results instantly.

However, the true power of this software lies not in its code, but in the hope it represents. This project was developed as a **social responsibility initiative** to support **Toprak Kaan Selvi**, a child battling **DMD (Duchenne Muscular Dystrophy)**, in his fight to access life-saving gene therapy.

---

## 🆕 What's New in V.5.0.0

> Our biggest update ever, built entirely on user feedback.

| # | Feature | Description |
|---|---------|-------------|
| 1 | 🔤 **Case-Sensitive Search** | Toggle exact match with a checkbox |
| 2 | 🧩 **Regex Mode** | Advanced patterns like `^error.*critical`, `\d{3}-\d{4}` |
| 3 | 🔗 **AND / OR Multi-Keyword** | `error AND critical` or `error OR warning` |
| 4 | 🕘 **Search History** | Last 20 searches saved, restored in one click |
| 5 | 📤 **Export Results** | Save results as Excel (.xlsx), CSV, or TXT |
| 6 | 🎨 **Theme Switcher** | Dark / Light / System — instant switch |

### Other Improvements
- ✅ **"How to Use"** guide shown automatically on startup
- ✅ **Scrollbar** added to results area
- ✅ **Right-click menu hint** added for new users
- ✅ **"SEARCHING..."** label now displays correctly in white
- ✅ Syntax highlighting **properly cleared** when toggled off
- ✅ Highlighting **auto-disabled** for large files (>1000 lines)
- ✅ Highlighting **paused during scrolling** for smooth experience
- ✅ PDF results **fully hidden** for unlicensed users (still counted in summary)
- ✅ **Features & Version Comparison** window added (Help menu)

---

## ✨ Full Feature List

### 🟢 Free Version

| Feature | Status |
|---------|--------|
| Search in text files (.txt, .js, .php, .css, .py, .html, etc.) | ✅ |
| Recursive subfolder scanning | ✅ |
| File name search | ✅ |
| Multi-format filtering | ✅ |
| AND / OR multi-keyword logic | ✅ |
| Regex (regular expression) mode | ✅ |
| Case-sensitive search | ✅ |
| Search history (last 20) | ✅ |
| Theme switcher (Dark / Light / System) | ✅ |
| Export results (Excel, CSV, TXT) | ✅ |
| Drag & drop folder support | ✅ |
| Stop search anytime | ✅ |
| Result display limit | First 3 |

### 💎 Full Version (Donors Only)

| Feature | Status |
|---------|--------|
| **Search inside PDF files** | 💎 |
| **PDF page & line details** | 💎 |
| **Word (.docx) paragraph details** | 💎 |
| **Unlimited results** | 💎 |
| **Built-in Text Editor** | 💎 |
| **Syntax Highlighting** (PHP, JS, CSS, Python, HTML...) | 💎 |
| **Line number display** | 💎 |
| **Find & Replace** (Ctrl+H) | 💎 |
| **Go to Line** (Ctrl+G) | 💎 |
| **Right-click → Edit in Editor** | 💎 |

---

## 📖 How to Use

### Basic Search
1. Type your search term in the **Search Term** field
2. Enter or drag your folder into the **Folder Path** field
3. Select a format filter (optional)
4. Click **🚀 START SEARCH**

### New: Multi-Keyword (AND / OR)
```
# Both keywords must appear (AND)
error AND critical

# Either keyword is enough (OR)
error OR warning
```

### New: Regex Mode
```regex
^error         # Lines starting with "error"
\.php$         # Lines ending with ".php"
error.*critical  # Lines with "error" then "critical"
\d{3}-\d{4}    # Phone format like 555-1234
```

### Working with Results
> **Right-click any file name** in the results to:
> - 📂 **Open Folder** — Opens the file's location in Explorer
> - 📝 **Edit in Editor** — Opens in built-in editor *(Full Version)*

---

## ❤️ How to Get the Full Version (License)?

Owning the Full Version of Alperi Search Pro also means becoming a hero!

1. Donate at least **400 TRY** (or equivalent) to the officially approved charity accounts below
2. Send your donation receipt to **alper.peri@gmail.com**
3. Include the **Device Code** shown in the program
4. Your Full Version license key will be sent to your email

---

## 🏛️ Official Campaign Information

| Info | Detail |
|------|--------|
| **Campaign Owner** | YASİN ALPARSLAN SELVİ |
| **Campaign ID** | `34.2024.2335` *(Officially approved by the Governorship of Turkey)* |
| **Website** | [toprakkaanselvi.org.tr](https://toprakkaanselvi.org.tr) |

### 🏦 Bank Accounts

| Currency | IBAN |
|----------|------|
| 🇹🇷 **TRY** | `TR60 0001 2001 2850 0001 1255 54` |
| 🇺🇸 **USD** | `TR18 0001 2001 2850 0023 0023 32` |
| 🇪🇺 **EUR** | `TR02 0001 2001 2850 0035 0016 17` |

---

## 📥 Download & Installation

Download the latest version (V.5.0.0) directly from SourceForge:

👉 **[Download Alperi Search Pro (SourceForge)](https://sourceforge.net/projects/alperi/files/Alperi_Kelime_Arama_Pro_Kurulum.exe/download)**

### System Requirements
- Windows 10 / 11 (64-bit)
- 50 MB disk space
- No internet connection required

---

## 📋 Changelog

| Version | Date | Highlights |
|---------|------|------------|
| **V.5.0.0** | March 2026 | Regex, AND/OR, history, export, theme switcher |
| V.4.0.1 | March 2026 | SEARCHING label fix, welcome screen |
| V.4.0.0 | March 2026 | File name search, 2-section results, advanced editor |

---

**Developer:** Alper Peri | [alperperi.com](https://alperperi.com)
